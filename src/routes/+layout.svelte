<script>
	let { children } = $props();

    import NavBar from '$lib/NavBar.svelte';
</script>

<NavBar />

{@render children()}