<script>
	import '../app.css';
    import Sidebar from "$lib/components/Sidebar.svelte";
	let { children } = $props();
</script>

<Sidebar />
{@render children()}
<div class="lg:h-20 h-40"></div>
