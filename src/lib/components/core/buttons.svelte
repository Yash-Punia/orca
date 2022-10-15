<script>
	import buttons from '$lib/components/designs/buttons';
</script>

<div class="w-2/3 mx-auto py-4">
	<!-- <h1 class="font-body text-xl border-b-2 w-fit border-black mb-4 rounded-md">Buttons</h1> -->
	<div class="grid lg:grid-cols-4 md:grid-cols-3 sm:grid-cols-2 grid-cols-1 place-items-center gap-8">
		{#each buttons as button}
			<svelte:component this={button}/>
		{/each}
	</div>
</div>
