<script context="module" lang="ts">
	export const prerender = true;
</script>

<script lang="ts">
	import Hello from '$lib/home/Hello.svelte';
	import About from '$lib/home/About.svelte';
	import Projects from '$lib/home/Projects.svelte';
</script>

<div class="min-h-screen">
	<Hello />
	<About />
	<hr class="max-w-5xl m-auto" />
	<Projects />
</div>
