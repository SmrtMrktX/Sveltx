<script lang="ts">
	import '../app.css';
	let { children } = $props();
	import Header from '$lib/components/layoutComponents/Header.svelte';
	import Footer from '$lib/components/layoutComponents/Footer.svelte';
</script>

<Header />

{@render children()}

<Footer />
