<svelte:head>
	<title>Frank Faith | Computer Science Student</title>
	<meta
		name="description"
		content="Frank Faith — Computer Science student building skills in networking and exploring web development."
	/>
</svelte:head>

<div class="min-h-screen bg-slate-950 text-slate-100">

	<!-- Navigation -->
	<nav class="border-b border-slate-800">
		<div class="max-w-5xl mx-auto px-6 py-5 flex flex-col gap-4 sm:flex-row sm:items-center sm:justify-between">

			<a href="/" class="font-bold text-lg tracking-tight">
				NetWithFaith
			</a>

			<div class="flex flex-wrap gap-x-4 gap-y-2 text-sm text-slate-400">
				<a href="#about" class="hover:text-white transition-colors">
					About
				</a>

				<a href="#learning" class="hover:text-white transition-colors">
					Learning
				</a>

				<a href="#contact" class="hover:text-white transition-colors">
					Contact
				</a>
			</div>

		</div>
	</nav>


	<!-- Hero -->
	<section class="max-w-5xl mx-auto px-6 py-24 md:py-32">

		<div class="max-w-3xl">

			<p class="text-blue-400 font-medium mb-5">
				Hello, I'm
			</p>

			<h1 class="text-5xl md:text-7xl font-bold tracking-tight">
				Frank Faith.
			</h1>

			<h2 class="mt-6 text-2xl md:text-4xl font-semibold text-slate-300 leading-tight">
				Computer Science student building skills in
				<span class="text-white">networking & web development.</span>
			</h2>

			<p class="mt-6 text-lg leading-relaxed text-slate-400 max-w-2xl">
				I'm currently working through my CCNA journey while also
				exploring web development through a 90-day building challenge.
			</p>

			<div class="flex flex-wrap gap-4 mt-8">

				<a
					href="https://github.com/NetWithFaith"
					target="_blank"
					rel="noopener noreferrer"
					class="rounded-md bg-white px-5 py-3 text-slate-950 font-medium hover:bg-slate-200 transition-colors"
				>
					GitHub
				</a>

				<a
					href="https://x.com/NetWithFaith"
					target="_blank"
					rel="noopener noreferrer"
					class="rounded-md border border-slate-700 px-5 py-3 font-medium hover:border-slate-400 transition-colors"
				>
					X
				</a>

			</div>

		</div>

	</section>


	<!-- About -->
	<section id="about" class="border-t border-slate-800">

		<div class="max-w-5xl mx-auto px-6 py-20">

			<p class="text-blue-400 font-medium mb-3">
				About me
			</p>

			<h2 class="text-3xl md:text-4xl font-bold">
				A little about my journey.
			</h2>

			<div class="mt-6 max-w-3xl space-y-4 text-lg leading-relaxed text-slate-400">

				<p>
					I'm a Computer Science student with a growing interest
					in networking and technology.
				</p>

				<p>
					I'm currently working through my CCNA journey and using
					Cisco Packet Tracer to practice the networking concepts
					I'm learning.
				</p>

				<p>
					I'm also exploring web development through a 90-day
					building challenge, where I'm learning by creating
					projects and documenting my progress.
				</p>

			</div>

		</div>

	</section>


	<!-- What I'm Learning -->
	<section id="learning" class="border-t border-slate-800">

		<div class="max-w-5xl mx-auto px-6 py-20">

			<p class="text-blue-400 font-medium mb-3">
				Currently learning
			</p>

			<h2 class="text-3xl md:text-4xl font-bold">
				What I'm learning.
			</h2>

			<div class="grid grid-cols-1 md:grid-cols-2 gap-6 mt-8">


				<!-- Networking -->
				<div class="border border-slate-800 rounded-lg p-6 md:p-8 hover:border-slate-600 transition-colors">

					<div class="text-3xl mb-4">
						🌐
					</div>

					<h3 class="text-2xl font-bold">
						Networking
					</h3>

					<p class="mt-4 text-slate-400 leading-relaxed">
						I'm working through my CCNA journey and building
						my understanding of how networks work. I'm also
						using Cisco Packet Tracer to practice what I learn.
					</p>

					<div class="flex flex-wrap gap-2 mt-6">

						<span class="text-sm border border-slate-700 rounded-full px-3 py-1">
							CCNA
						</span>

						<span class="text-sm border border-slate-700 rounded-full px-3 py-1">
							Packet Tracer
						</span>

						<span class="text-sm border border-slate-700 rounded-full px-3 py-1">
							IP Addressing
						</span>

						<span class="text-sm border border-slate-700 rounded-full px-3 py-1">
							Subnetting
						</span>

						<span class="text-sm border border-slate-700 rounded-full px-3 py-1">
							Routing
						</span>

						<span class="text-sm border border-slate-700 rounded-full px-3 py-1">
							Switching
						</span>

					</div>

				</div>


				<!-- Web Development -->
				<div class="border border-slate-800 rounded-lg p-6 md:p-8 hover:border-slate-600 transition-colors">

					<div class="text-3xl mb-4">
						💻
					</div>

					<h3 class="text-2xl font-bold">
						Web Development
					</h3>

					<p class="mt-4 text-slate-400 leading-relaxed">
						I'm exploring web development through a 90-day
						building challenge. I'm learning by building,
						sharing my progress, and getting familiar with
						modern web development tools.
					</p>

					<div class="flex flex-wrap gap-2 mt-6">

						<span class="text-sm border border-slate-700 rounded-full px-3 py-1">
							SvelteKit
						</span>

						<span class="text-sm border border-slate-700 rounded-full px-3 py-1">
							Tailwind CSS
						</span>

						<span class="text-sm border border-slate-700 rounded-full px-3 py-1">
							Git
						</span>

						<span class="text-sm border border-slate-700 rounded-full px-3 py-1">
							GitHub
						</span>

					</div>

				</div>

			</div>


			<!-- Small learning note -->
			<p class="mt-8 text-sm text-slate-500">
				I'm learning, experimenting, and adding to these skills as I progress.
			</p>

		</div>

	</section>


	<!-- Contact -->
	<section id="contact" class="border-t border-slate-800">

		<div class="max-w-5xl mx-auto px-6 py-20">

			<p class="text-blue-400 font-medium mb-3">
				Contact
			</p>

			<h2 class="text-3xl md:text-4xl font-bold">
				Let's connect.
			</h2>

			<p class="mt-4 text-lg text-slate-400">
				Want to say hello or follow my journey?
			</p>

			<div class="flex flex-wrap gap-5 mt-8">

				<a
					href="mailto:frankfaith2525@gmail.com"
					class="text-slate-300 hover:text-white transition-colors underline underline-offset-4"
				>
					Email
				</a>

				<a
					href="https://github.com/NetWithFaith"
					target="_blank"
					rel="noopener noreferrer"
					class="text-slate-300 hover:text-white transition-colors underline underline-offset-4"
				>
					GitHub
				</a>

				<a
					href="https://x.com/NetWithFaith"
					target="_blank"
					rel="noopener noreferrer"
					class="text-slate-300 hover:text-white transition-colors underline underline-offset-4"
				>
					X
				</a>

			</div>

		</div>

	</section>


	<!-- Footer -->
	<footer class="border-t border-slate-800">

		<div class="max-w-5xl mx-auto px-6 py-8 text-sm text-slate-500">

			<p>
				© 2026 Frank Faith. Built while learning.
			</p>

		</div>

	</footer>

</div>