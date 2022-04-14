<script lang="ts">
	const iconPaths = [
		'svelte.png',
		'ts.png',
		'tailwind.png',
		'firebase.png',
		'react.svg',
		'next.svg',
		'flutter.svg',
		'node.svg',
		'git.png',
		'mysql.png'
	];
</script>

<div class="flex flex-wrap items-center justify-center gap-8 max-w-none lg:max-w-3xl lg:p-8">
	{#each iconPaths as path}
		<img src={'/icons/' + path} class="h-16 aspect-auto m-4" alt="" />
	{/each}
</div>

<style lang="postcss">
</style>
