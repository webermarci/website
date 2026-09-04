<script lang="ts">
	import { onMount } from 'svelte';
	import './layout.css';
	import favicon from '$lib/assets/favicon.svg';

	let { children } = $props();

	onMount(() => {
		let cancelled = false;

		const initializePostHog = () => {
			void import('posthog-js/dist/module.slim').then(({ default: posthog }) => {
				if (cancelled) return;

				posthog.init('phc_4XB2LcqTutCvDbtvimDaGsOt04nsZ4f23SdJZbDDdEZ', {
					api_host: 'https://eu.i.posthog.com',
					defaults: '2026-01-30',
					person_profiles: 'always'
				});
			});
		};

		let timeoutId: number | undefined;
		let idleCallbackId: number | undefined;

		if ('requestIdleCallback' in window) {
			idleCallbackId = window.requestIdleCallback(initializePostHog, { timeout: 2000 });
		} else {
			timeoutId = window.setTimeout(initializePostHog);
		}

		return () => {
			cancelled = true;

			if (idleCallbackId !== undefined) window.cancelIdleCallback(idleCallbackId);
			if (timeoutId !== undefined) window.clearTimeout(timeoutId);
		};
	});
</script>

<svelte:head>
	<title>webermarci</title>
	<link rel="icon" href={favicon} />
	<meta
		name="description"
		content="Marci Wéber is a Budapest-based software engineer focused on quality, performance, backend systems, and industrial automation."
	/>
</svelte:head>

{@render children()}
