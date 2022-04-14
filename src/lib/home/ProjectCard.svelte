<script lang="ts">
	import type { ProjectCard } from '$lib/types';

	export let project: ProjectCard;
</script>

<a
	href={project.href}
	class="rounded-md py-4 px-8 flex flex-col max-w-sm shadow-md bg-white gap-y-4 border-[1px] border-slate-200 
            transition-all ease-linear hover:shadow-lg group w-full"
>
	<div class="flex items-center justify-between">
		<div class="flex gap-x-4 items-center">
			<img
				src={`/projectIcons/${project.iconName}`}
				width="48"
				height="48"
				class="rounded-full"
				alt=""
			/>
			<span
				class="border-b-2 {{}} mb-0.5 group-hover:mb-0 group-hover:border-b-4 transition-all text-lg "
				style={`border-color: ${project.color};`}
			>
				{project.name}
			</span>
		</div>
		<!-- {#if project.workInProgress}
			<span class="text-slate-400 text-xs "> In Progress </span>
		{/if} -->
	</div>
	{project.description}
</a>
