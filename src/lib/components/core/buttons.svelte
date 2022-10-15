<script>
	import buttons from '$lib/components/designs/buttons';
</script>

<div class="w-2/3 mx-auto py-4">
	<div class="grid lg:grid-cols-4 md:grid-cols-3 sm:grid-cols-2 grid-cols-1 place-items-center gap-8">
		{#each buttons as button}
			<svelte:component this={button}/>
		{/each}
	</div>
</div>
