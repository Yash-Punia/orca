<script>
	import buttons from '$lib/components/designs/buttons';
</script>

<div class="w-2/3 mx-auto">
	<h1 class="font-body text-2xl border-b-4 w-fit border-black mb-4 rounded-md">Buttons</h1>
	<div class="grid grid-cols-3 place-items-center gap-4">
		{#each buttons as button}
			<svelte:component this={button}/>
		{/each}
	</div>
</div>
