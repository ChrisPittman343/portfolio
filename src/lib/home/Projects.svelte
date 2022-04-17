<script lang="ts">
	import ProjectCard from '$lib/home/ProjectCard.svelte';
	import type { ProjectCard as ProjectCardI } from '$lib/types';

	const projects: ProjectCardI[] = [
		{
			name: 'RankEm',
			description: 'Platform for ranking options against one another',
			href: 'https://rankem.vercel.app/',
			workInProgress: true,
			iconName: 'rankEm.svg',
			color: '#5364C9'
		},
		// {
		// 	name: 'process.physics',
		// 	description: 'Physics tutoring site that focuses on high quality video explanations',
		// 	href: '/',
		// 	workInProgress: true,
		// 	iconName: 'default.jpg',
		// 	color: '#30ABF1'
		// },
		{
			name: 'Grindset',
			description:
				'Mobile app that helps you keep track of and maintain streaks of healthy activities',
			href: 'https://github.com/ChrisPittman343/grindset',
			workInProgress: true,
			iconName: 'default.jpg',
			color: '#E42D22'
		},
		{
			name: 'pxls',
			description: 'Tool for getting the color palette of pixel art',
			href: 'https://pxls.vercel.app/',
			workInProgress: true,
			iconName: 'pxls.png',
			color: '#1f1f1f'
		}
		// {
		// 	name: 'Taskee',
		// 	description: 'Minimal Chrome extension for managing your to-dos.',
		// 	href: '/',
		// 	workInProgress: true,
		// 	iconName: 'default.jpg',
		// 	color: '#10b981'
		// },
		// {
		// 	name: 'Deskercise',
		// 	description: 'Simple mobile app that reminds you to take care of your wrists when working',
		// 	href: '/',
		// 	workInProgress: true,
		// 	iconName: 'default.jpg',
		// 	color: '#10b981'
		// }
	];
</script>

<section
	id="projects"
	class="max-w-7xl min-h-screen m-auto p-4 pt-20 flex flex-col items-center gap-y-8"
>
	<h1 class="text-3xl">Projects</h1>
	<h2 class="text-xl px-8">Here are some of my favorite projects I am and have been working on.</h2>

	<div class="flex flex-wrap gap-8 justify-evenly lg:m-8">
		{#each projects as project}
			<ProjectCard {project} />
		{/each}
	</div>
</section>

<style lang="postcss">
</style>
