<script>
	import navbars from '$lib/components/designs/navbars/';
</script>

<div class="w-2/3 mx-auto py-4">
	<div class="flex flex-col">
		{#each navbars as navbar}
			<svelte:component this={navbar}/>
		{/each}
	</div>
</div>
