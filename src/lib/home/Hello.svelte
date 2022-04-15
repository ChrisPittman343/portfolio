<section
	id="intro"
	class="min-h-screen flex flex-col justify-center bg-fixed bg-cover bg-no-repeat bg-right items-center lg:items-start"
>
	<div
		class="flex flex-col gap-8 max-w-lg lg:max-w-3xl p-12 lg:py-12 lg:px-16 rounded-lg bg-white lg:ml-16 m-8 shadow-2xl"
	>
		<div class="flex justify-between items-center">
			<h1 class=" text-4xl sm:text-6xl lg:text-8xl">Hi,<br />I'm Chris!</h1>
			<span class="text-7xl hidden sm:block lg:text-9xl">👋</span>
		</div>
		<h2 class="text-xl lg:text-3xl">
			I'm a first year Web &amp; Mobile Computing student at RIT who loves web development, front to
			back.
		</h2>
		<div class="flex gap-x-6 justify-end">
			<a href="/chrisPittmanResume.pdf" target="_blank">
				<img src="/icons/resume.svg" alt="Resume" />
			</a>
			<a href="https://github.com/chrispittman343" target="_blank">
				<img src="/icons/github.svg" alt="Github" />
			</a>
			<a href="https://www.linkedin.com/in/chris-pittman-b83692232/" target="_blank">
				<img src="/icons/linkedin.svg" alt="LinkedIn" />
			</a>
		</div>
	</div>
</section>

<style lang="postcss">
	#intro {
		background-image: url('/abstract.jpg');
	}
	a img {
		@apply w-7 aspect-square transition-opacity opacity-60;
	}

	a:hover img {
		@apply opacity-100;
	}
</style>
