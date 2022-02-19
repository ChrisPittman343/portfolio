<script lang="ts">
	import Skills from '$lib/Skills.svelte';
</script>

<section
	id="about"
	class="max-w-9xl min-h-screen m-auto p-4 pt-20 flex flex-col items-center gap-y-8"
>
	<h1 class="text-3xl">About</h1>
	<h2 class="max-w-3xl text-xl">
		<!-- Todo: I hate this section -->
		If I'm not at my computer, I am probably outside. I'm an avid rock climber that enjoys gyms and crags
		alike, a skier in the winter months, and a swimmer when my hands need a break and there's no snow
		to shred. However, when I am on my computer, I am programming something fun!
		<div class="min-h-[32px]" />
		Although my go-to stack for personal projects is a SvelteKit, TypeScript, and TailwindCSS frontend
		with a Firebase backend, these are all of the technologies I'm comfortable using.
	</h2>
	<Skills />
</section>

<style lang="postcss">
</style>
