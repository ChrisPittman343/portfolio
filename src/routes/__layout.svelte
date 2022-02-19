<script lang="ts">
	import Nav from '$lib/nav/Nav.svelte';
	import Footer from '$lib/Footer.svelte';
	import '../app.css';
</script>

<svelte:head>
	<title>Chris Pittman - Portfolio</title>
</svelte:head>

<Nav />

<main class="scroll-smooth">
	<slot />
</main>

<Footer />
