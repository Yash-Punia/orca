<script>
	import Buttons from '$lib/components/core/buttons.svelte';
	import Navbars from '$lib/components/core/navbars.svelte';
	import { state } from '$lib/stores/global'
</script>

{#if $state == 'buttons'}
	<Buttons />
{:else if $state == 'navbars'}
	<Navbars />
{/if}