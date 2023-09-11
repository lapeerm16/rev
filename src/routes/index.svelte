<script>
	import Bdf from '../lib/Bdf.svelte';

	const bdfs = [
		{ id: 0 },
		{ id: 1 },
		{ id: 2 },
		{ id: 3 }
	];
</script>

<main>
	{#each bdfs as bdf (bdf.id)}
		<Bdf/>
	{/each}
<main>

<style>

</style>