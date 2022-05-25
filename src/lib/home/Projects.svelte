<script lang="ts">
	import ProjectCard from '$lib/home/ProjectCard.svelte';
	import type { ProjectCard as ProjectCardI } from '$lib/types';

	const projects: ProjectCardI[] = [
		{
			name: 'Ten Men',
			description: 'Stat tracker for private CS:GO matches between friends',
			href: 'https://ten-men.herokuapp.com/',
			github: 'https://github.com/ChrisPittman343/ten-men',
			workInProgress: false,
			iconName: '10m.png',
			color: '#4E6AFC'
		},
		{
			name: 'pxls',
			description: 'Tool for artists that finds the color palette of pixel art',
			href: 'https://pxls.vercel.app/',
			github: 'https://github.com/ChrisPittman343/pxls',
			workInProgress: false,
			iconName: 'pxls.png',
			color: '#1f1f1f'
		},
		{
			name: 'RankEm',
			description: 'Platform for ranking options against one another',
			href: 'https://rankem.vercel.app/',
			github: 'https://github.com/ChrisPittman343/rank-em',
			workInProgress: true,
			iconName: 'rankEm.svg',
			color: '#5364C9'
		},
		{
			name: 'Lyrik',
			description: 'Lyric guessing game for popular songs, according to Musixmatch',
			href: 'https://lyrik.vercel.app/',
			github: 'https://github.com/ChrisPittman343/lyrik',
			workInProgress: false,
			iconName: 'lyrik.png',
			color: '#F1D765'
		},
		{
			name: 'process.physics',
			description: 'Physics tutoring that emphasizes simple, repeatable problem solving processes',
			href: '/',
			workInProgress: true,
			iconName: 'default.jpg',
			color: '#30ABF1'
		}
	];
</script>

<section
	id="projects"
	class="max-w-6xl min-h-screen m-auto p-4 pt-12 flex flex-col items-center gap-y-8"
>
	<header class="text-center">
		<h1 class="text-3xl pb-2">Projects</h1>
		<p>Here are some of my favorite projects I've been working on.</p>
	</header>

	<div class="flex flex-wrap gap-8 justify-evenly lg:m-8">
		{#each projects as project}
			<ProjectCard {project} />
		{/each}
	</div>
</section>

<style lang="postcss">
</style>
