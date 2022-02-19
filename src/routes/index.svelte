<script context="module" lang="ts">
	export const prerender = true;
</script>

<script lang="ts">
	import Hello from '$lib/sections/Hello.svelte';
	import About from '$lib/sections/About.svelte';
	import Projects from '$lib/sections/Projects.svelte';
</script>

<div class="min-h-screen">
	<Hello />
	<About />
	<Projects />
</div>
