<script>
	import Navbar from "$lib/components/core/navbar.svelte";
    import "../app.css";
</script>

<svelte:head>
    <title>Orca</title>
</svelte:head>


<Navbar/>
<slot />