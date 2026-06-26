<svelte:head>
	<title>Azin Programming Language</title>
	<meta
		name="description"
		content="Azin is a modern programming language currently under development."
	/>
</svelte:head>

<script lang="ts">
	const year = new Date().getFullYear();
</script>

<div class="min-h-screen flex flex-col items-center justify-center bg-zinc-950 px-6 text-center text-white">
	<p class="mb-4 text-lg font-medium tracking-[0.35em] text-sky-400 uppercase">
		Azin Programming Language
	</p>

	<h1 class="max-w-5xl text-7xl font-black leading-tight md:text-8xl">
		Under Construction.
	</h1>

	<p class="mt-6 max-w-2xl text-xl text-zinc-400">
		The official Azin website is currently being built.
		Check back soon for documentation, downloads, and updates.
	</p>

	<div class="mt-10 flex gap-4">
		<a
			href="https://github.com/azin-lang/azin"
			class="rounded-lg bg-sky-500 px-7 py-3 font-semibold transition hover:bg-sky-400"
		>
			GitHub
		</a>

		<span class="rounded-lg border border-zinc-700 px-7 py-3 text-zinc-300">
			Coming Soon
		</span>
	</div>

	<p class="mt-16 text-sm text-zinc-600">
		© {year} Azin Language Project
	</p>
</div>