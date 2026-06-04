<script lang="ts">
	import './layout.css';
	import favicon from '$lib/assets/favicon.svg';

	let { children } = $props();
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
