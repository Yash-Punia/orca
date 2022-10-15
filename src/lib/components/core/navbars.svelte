<script>
	import navbars from '$lib/components/designs/navbars/';
</script>

<div class="w-2/3 mx-auto py-4">
	<!-- <h1 class="font-body text-xl border-b-2 w-fit border-black mb-4 rounded-md">navbars</h1> -->
	<div class="flex flex-col">
		{#each navbars as navbar}
			<svelte:component this={navbar}/>
		{/each}
	</div>
</div>
