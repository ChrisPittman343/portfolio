<script lang="ts">
	import Skills from './Skills.svelte';
</script>

<section
	id="about"
	class="max-w-9xl min-h-screen m-auto p-4 px-12 pt-20 flex flex-col items-center gap-y-8"
>
	<h1 class="text-3xl">About</h1>
	<h2 class="max-w-3xl text-xl leading-9">
		If I'm not at my computer, chances are that I am either rock climbing (V7 indoor, V2 outdoor),
		or training to climb harder at the gym. Some of my more casual hobbies include swimming, skiing,
		drawing pixel art, and making music.
		<div class="min-h-[32px]" />
		But when I'm not doing any of that, I'm programming something fun! I am especially well practiced
		with SvelteKit, TypeScript, TailwindCSS, and Firebase (My go-to stack for personal projects), but
		I am also comfortable using the following technologies:
	</h2>
	<Skills />
</section>

<style lang="postcss">
</style>
