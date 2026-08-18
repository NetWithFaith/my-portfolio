<script lang="ts">
import './layout.css'
	let { children } = $props();
</script>

<svelte:head>
	<meta name="viewport" content="width=device-width, initial-scale=1" />
</svelte:head>

<div class="min-h-screen bg-slate-950 text-white">

	<header class="border-b border-slate-800 bg-slate-950">
	<nav class="mx-auto max-w-6xl px-6 py-5">

		<div class="flex items-center justify-between">

			<!-- Logo -->
			<a
				href="/"
				class="text-lg font-bold tracking-tight text-white sm:text-xl"
			>
				NetWithFaith<span class="text-blue-400">.</span>
			</a>

			<!-- Desktop navigation -->
			<div class="hidden items-center gap-7 text-sm font-medium sm:flex">

				<a
					href="/"
					class="text-slate-300 transition hover:text-blue-400"
				>
					Home
				</a>

				<a
					href="/about"
					class="text-slate-300 transition hover:text-blue-400"
				>
					About
				</a>

				<a
					href="/work"
					class="text-slate-300 transition hover:text-blue-400"
				>
					Work
				</a>

				<a
					href="/contact"
					class="rounded-full bg-blue-600 px-5 py-2.5 text-white transition hover:bg-blue-500"
				>
					Contact
				</a>

			</div>

			<!-- Mobile navigation -->
			<div class="flex items-center gap-5 sm:hidden">

				<!-- Home -->
				<a
					href="/"
					aria-label="Home"
					title="Home"
					class="text-slate-300 transition hover:text-blue-400"
				>
					<svg
						xmlns="http://www.w3.org/2000/svg"
						viewBox="0 0 24 24"
						fill="none"
						stroke="currentColor"
						stroke-width="1.8"
						class="h-5 w-5"
					>
						<path
							stroke-linecap="round"
							stroke-linejoin="round"
							d="m2.25 12 9.204-7.513a.75.75 0 0 1 .948 0L21.75 12M4.5 9.75v9.75a.75.75 0 0 0 .75.75h4.5v-6h3.5v6h4.5a.75.75 0 0 0 .75-.75V9.75"
						/>
					</svg>
				</a>

				<!-- About -->
				<a
					href="/about"
					aria-label="About"
					title="About"
					class="text-slate-300 transition hover:text-blue-400"
				>
					<svg
						xmlns="http://www.w3.org/2000/svg"
						viewBox="0 0 24 24"
						fill="none"
						stroke="currentColor"
						stroke-width="1.8"
						class="h-5 w-5"
					>
						<path
							stroke-linecap="round"
							stroke-linejoin="round"
							d="M15.75 6a3.75 3.75 0 1 1-7.5 0 3.75 3.75 0 0 1 7.5 0ZM4.5 20.25a7.5 7.5 0 0 1 15 0"
						/>
					</svg>
				</a>

				<!-- Work -->
				<a
					href="/work"
					aria-label="Work"
					title="Work"
					class="text-slate-300 transition hover:text-blue-400"
				>
					<svg
						xmlns="http://www.w3.org/2000/svg"
						viewBox="0 0 24 24"
						fill="none"
						stroke="currentColor"
						stroke-width="1.8"
						class="h-5 w-5"
					>
						<path
							stroke-linecap="round"
							stroke-linejoin="round"
							d="M20.25 14.15v4.35a1.5 1.5 0 0 1-1.5 1.5H5.25a1.5 1.5 0 0 1-1.5-1.5v-4.35M8.25 6.75h7.5l1.5 3H6.75l1.5-3ZM3.75 9.75h16.5v4.5a3 3 0 0 1-3 3h-10.5a3 3 0 0 1-3-3v-4.5Z"
						/>
					</svg>
				</a>

				<!-- Contact -->
				<a
					href="/contact"
					aria-label="Contact"
					title="Contact"
					class="text-blue-400 transition hover:text-blue-300"
				>
					<svg
						xmlns="http://www.w3.org/2000/svg"
						viewBox="0 0 24 24"
						fill="none"
						stroke="currentColor"
						stroke-width="1.8"
						class="h-5 w-5"
					>
						<path
							stroke-linecap="round"
							stroke-linejoin="round"
							d="M21.75 6.75v10.5a2.25 2.25 0 0 1-2.25 2.25H4.5a2.25 2.25 0 0 1-2.25-2.25V6.75m19.5 0A2.25 2.25 0 0 0 19.5 4.5h-15A2.25 2.25 0 0 0 2.25 6.75m19.5 0-9.75 6.75-9.75-6.75"
						/>
					</svg>
				</a>

			</div>

		</div>

	</nav>
</header>


	{@render children()}


	<footer class="border-t border-slate-800 bg-slate-950">

		<div class="mx-auto flex max-w-6xl items-center justify-between px-6 py-8">

			<p class="text-sm text-slate-500">
				© {new Date().getFullYear()} Frank Faith.
			</p>

			<div class="flex gap-5 text-sm">

				<a
					href="https://github.com/NetWithFaith"
					target="_blank"
					rel="noreferrer"
					class="text-slate-500 hover:text-white"
				>
					GitHub
				</a>

				<a
					href="https://www.linkedin.com/in/faith-frank-119a94317?utm_source=share_via&utm_content=profile&utm_medium=member_andriod"
					target="_blank"
					rel="noreferrer"
					class="text-slate-500 hover:text-blue-400"
				>
					LinkedIn
				</a>

				<a
					href="https://x.com/NetWithFaith"
					target="_blank"
					rel="noreferrer"
					class="text-slate-500 hover:text-white"
				>
					X
				</a>

			</div>

		</div>

	</footer>

</div>