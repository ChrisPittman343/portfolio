<script lang="ts">
	const iconPaths = [
		'ts.png',
		'react.svg',
		'next.svg',
		'svelte.png',
		'tailwind.png',
		'flutter.svg',
		'node.svg',
		'git.png',
		'firebase.png',
		'mysql.png'
	];
</script>

<div class="flex flex-wrap items-center justify-center gap-8 max-w-none lg:max-w-3xl p-8">
	{#each iconPaths as path}
		<!-- svelte-ignore a11y-missing-attribute -->
		<img src={'/icons/' + path} class="h-16 aspect-auto m-4" />
	{/each}
</div>

<style lang="postcss">
</style>
