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

<div class="min-h-screen flex items-center justify-center bg-zinc-950 text-white">
	<div class="max-w-3xl text-center px-6">
		<p class="text-sky-400 font-semibold tracking-[0.3em] uppercase mb-4">
			Azin Programming Language
		</p>

		<h1 class="text-6xl md:text-7xl font-black mb-6">
			Building the future,
			<span class="text-sky-400">one compiler at a time.</span>
		</h1>

		<p class="text-zinc-400 text-lg mb-10 leading-relaxed">
			The official Azin website is currently under construction.
			Documentation, downloads, examples, and more are on the way.
		</p>

		<div class="flex justify-center gap-4 flex-wrap">
			<a
				href="https://github.com/azin-lang/azin"
				class="rounded-xl bg-sky-500 px-6 py-3 font-semibold transition hover:bg-sky-400"
			>
				GitHub
			</a>

			<span
				class="rounded-xl border border-zinc-700 px-6 py-3 text-zinc-300"
			>
				🚧 Website Coming Soon
			</span>
		</div>

		<div class="mt-16 text-sm text-zinc-600">
			© {year} Azin Language Project
		</div>
	</div>
</div>