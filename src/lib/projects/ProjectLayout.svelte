<script lang="ts">
	import type { ProjectPage } from '$lib/types';

	export let layoutProps: ProjectPage;
</script>

<div class="pt-16 p-8 min-h-screen max-w-2xl lg:max-w-6xl mx-auto">
	<h1 class="text-3xl">
		<slot name="name" />
	</h1>

	<div class="">
		<div class="w-4/5 bg-slate-200 aspect-video" />
		<div class="flex items-center gap-x-4">
			<a target="_blank" href="https://github.com">
				<img src="/icons/github.svg" />
			</a>
			<a target="_blank" href="https://github.com">
				<img src="/icons/github.svg" />
			</a>
		</div>
		<p>
			<slot name="description"
				>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quibusdam beatae quam eum iure.
				Quidem sapiente quos nisi, provident neque possimus deleniti deserunt dolores quibusdam
				maiores voluptas laudantium ducimus. Corrupti pariatur ad sequi consequuntur consectetur
				dolor ea doloribus numquam quaerat, dicta odio tenetur quibusdam maxime a quisquam magni
				porro.
			</slot>
		</p>
	</div>
</div>

<style lang="postcss">
</style>
