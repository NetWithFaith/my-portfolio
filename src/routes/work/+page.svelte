<script lang="ts">
	const projects = [
		{
			number: '01',
			title: 'Personal Portfolio',
			description:
				'A responsive personal portfolio built with SvelteKit and Tailwind CSS to showcase my skills, projects, and learning journey.',
			technologies: ['SvelteKit', 'Tailwind CSS', 'TypeScript'],
			comingSoon: false
		},
		{
	number: '02',
	title: 'Networking Projects',
	description:
		'Hands-on networking projects covering IP addressing, subnetting, routing, switching, and network troubleshooting.',
	technologies: ['Cisco Packet Tracer', 'CCNA', 'Networking'],
	comingSoon: true
},
		{
			number: '03',
			title: 'Future Project',
			description:
				'A new project that I will build as I continue developing my full-stack development skills.',
			technologies: ['SvelteKit', 'JavaScript', 'PostgreSQL'],
			comingSoon: true
		}
	];
</script>

<svelte:head>
	<title>Work — Frank Faith</title>

	<meta
		name="description"
		content="Projects and technical work by Frank Faith."
	/>
</svelte:head>

<main class="bg-slate-950">

	<section class="mx-auto max-w-6xl px-6 py-24 lg:py-32">

		<div class="max-w-3xl">

			<p class="text-sm font-bold uppercase tracking-widest text-blue-400">
				Work
			</p>

			<h1
				class="mt-5 text-5xl font-bold tracking-tight text-white sm:text-6xl"
			>
				Things I've built.
			</h1>

			<p class="mt-7 text-lg leading-8 text-slate-400">
				A collection of projects and technical work from my learning
				journey.
			</p>

		</div>


		<div class="mt-16 space-y-5">

			{#each projects as project}

				<article
					class="rounded-2xl border border-slate-800 bg-slate-900 p-7 transition duration-300 hover:-translate-y-1 hover:border-blue-500 sm:p-9"
				>

					<div class="flex gap-5">

						<span class="font-mono text-sm font-medium text-blue-400">
							{project.number}
						</span>

						<div class="flex-1">

							<div class="flex flex-wrap items-center gap-3">
	<h2 class="text-2xl font-bold text-white">
		{project.title}
	</h2>

	{#if project.number === '01'}
	<span
		class="rounded-full bg-blue-500/10 px-3 py-1 text-xs font-medium text-blue-400"
	>
		This Site
	</span>
{:else if project.comingSoon}
	<span
		class="rounded-full bg-slate-800 px-3 py-1 text-xs font-medium text-slate-400"
	>
		Coming Soon
	</span>
{/if}
</div>

							<p class="mt-4 max-w-2xl leading-7 text-slate-400">
								{project.description}
							</p>

							<div class="mt-6 flex flex-wrap gap-2">

								{#each project.technologies as technology}

									<span
										class="rounded-full bg-slate-800 px-3 py-1.5 text-xs font-medium text-slate-300"
									>
										{technology}
									</span>

								{/each}

							</div>

						</div>

					</div>

				</article>

			{/each}

		</div>

	</section>

</main>