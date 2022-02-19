<script lang="ts">
	import ProjectCard from '$lib/projects/ProjectCard.svelte';
	import type { Project } from '$lib/types';

	const projects: Project[] = [
		{
			name: 'Power Ranker',
			description:
				'A web app for ranking whatever you want. Additionally, it tracks rankings over time.',
			href: '/'
		},
		{
			name: 'Interval Routines',
			description: 'A mobile app for interval based workouts you do regularly.',
			href: '/'
		},
		{
			name: 'StreamLine',
			description: 'A way for swim coaches to build workouts using a simple GUI.',
			href: '/'
		},

		{
			name: 'PXLS',
			description: 'A tool for getting the color palette of pixel art.',
			href: '/'
		},
		{
			name: 'Taskee',
			description: 'A minimal Chrome extension for managing your to-dos.',
			href: '/'
		},
		{
			name: 'IsOpen',
			description: "A simple app for telling your customers if you're open or not.",
			href: '/'
		}
	];
</script>

<section
	id="projects"
	class="max-w-7xl min-h-screen m-auto p-4 pt-20 flex flex-col items-center gap-y-8"
>
	<h1 class="text-3xl">Projects</h1>
	<h2 class="text-xl">Here are some of my favorite projects I am and have been working on.</h2>

	<div class="flex flex-wrap gap-8 justify-evenly m-8">
		{#each projects as project}
			<ProjectCard {project} />
		{/each}
	</div>
</section>

<style lang="postcss">
</style>
