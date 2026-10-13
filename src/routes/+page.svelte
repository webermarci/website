<script>
	import Intro from '#lib/components/Intro.svelte';
	import Experience from '#lib/components/Experience.svelte';
	import Projects from '#lib/components/Projects.svelte';
</script>

<main class="mx-auto grid max-w-384 lg:grid-cols-2">
	<div class="p-3 md:p-5 lg:p-5 xl:p-10">
		<Intro />
		<Projects />
	</div>
	<div class="p-3 md:p-5 lg:p-5 xl:p-10">
		<Experience />
	</div>
</main>
