<script lang="ts">
	import type { Project } from '$lib/types';

	export let project: Project;
	// Colors = teal, blue, yellow, amber, red, emerald
</script>

<a
	href={project.href}
	target="_blank"
	class="rounded-md py-4 px-8 flex flex-col max-w-sm shadow-md bg-white gap-y-4 border-[1px] border-slate-200 
            transition-all ease-linear hover:shadow-lg group"
>
	<div class="flex gap-x-4 items-center">
		<!-- svelte-ignore a11y-missing-attribute -->
		<img src="/default.jpg" width="48" height="48" class="rounded-full" />
		<span
			class="border-b-2 border-emerald-500 mb-0.5 group-hover:mb-0 group-hover:border-b-4 transition-all text-lg"
		>
			{project.name}
		</span>
	</div>
	{project.description}
</a>
