<script context="module" lang="ts">
	export const prerender = true;
</script>

<script lang="ts">
	import Hello from '$lib/home/Hello.svelte';
	import Projects from '$lib/home/Projects.svelte';
</script>

<div class="min-h-screen">
	<Hello />
	<Projects />
</div>
