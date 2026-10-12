<script lang="ts">
	import './layout.css';

	import favicon from '#lib/assets/favicon.svg';
	import aleoLatin from '#lib/assets/fonts/aleo/aleo-latin.woff2?url';
	import manropeLatin from '#lib/assets/fonts/manrope/manrope-latin.woff2?url';

	let { children } = $props();
</script>

<svelte:head>
	<title>webermarci</title>
	<link rel="icon" href={favicon} />
	<link rel="preload" href={aleoLatin} as="font" type="font/woff2" crossorigin="anonymous" />
	<link rel="preload" href={manropeLatin} as="font" type="font/woff2" crossorigin="anonymous" />
	<meta
		name="description"
		content="Marci Wéber is a Budapest-based software engineer focused on quality, performance, backend systems, and industrial automation."
	/>
</svelte:head>

{@render children()}
