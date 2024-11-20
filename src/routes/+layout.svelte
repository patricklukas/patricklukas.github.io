<script>
	let { children } = $props();
    export const prerender = true;

    import NavBar from '$lib/NavBar.svelte';
</script>

<NavBar />

{@render children()}