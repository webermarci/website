<script lang="ts">
	import { onMount } from 'svelte';
	import { draw } from 'svelte/transition';
	import { sineInOut } from 'svelte/easing';
	let showW = $state(false);
	let showM = $state(false);

	onMount(() => {
		setTimeout(() => {
			showW = true;
		});

		setTimeout(() => {
			showM = true;
		}, 900);
	});
</script>

<svg
	xmlns="http://www.w3.org/2000/svg"
	viewBox="-20 -20 150 180"
	stroke="currentColor"
	stroke-linecap="butt"
	stroke-linejoin="round"
	stroke-width="16"
	fill="none"
	class="w-24"
	aria-hidden="true"
>
	{#if showM}
		<path
			class="text-slate-400 will-change-transform"
			in:draw={{ duration: 1500, easing: sineInOut }}
			d="M5 135 L35 70 L55 105 L75 70 L105 135"
		/>
	{/if}

	{#if showW}
		<path
			class="text-slate-400 will-change-transform"
			in:draw={{ duration: 1500, easing: sineInOut }}
			d="M5 5 L35 70 L55 35 L75 70 L105 5"
		/>
	{/if}
</svg>
