<script>
	import Navbar from '$lib/components/core/orca-navbar.svelte';
	import Sidebar from '$lib/components/core/orca-sidebar.svelte';
	import '../app.css';
</script>

<svelte:head>
	<title>Orca</title>
</svelte:head>

<div class="min-h-screen">
	<Navbar />
    <div class="grid grid-cols-[1fr,11fr] min-h-full">
        <Sidebar />
        <slot />
    </div>
</div>
