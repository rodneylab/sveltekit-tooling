<script>
	import '@fontsource/montserrat';
	import '@fontsource/hind';
	import '$lib/styles/global.css';
</script>

<svelte:head>
	<title>SvelteKit Tooling Example Repo</title>
	<meta
		name="description"
		content="SvelteKit tooling: we look at 7 tools you can add to streamline your Svelte continuous integration (CI) and development processes."
	/>
</svelte:head>

<main class="container">
	<div class="content">
		<h1>sveltekit-tooling</h1>
		<p>SvelteKit Tooling Example Repo</p>
	</div>
</main>

<style>
	.container {
		display: flex;
		min-height: 100vh;
		background-image: linear-gradient(
			to top right,
			var(--colour-theme-lighter-20),
			var(--colour-theme)
		);
	}

	.content {
		background-image: linear-gradient(
			to bottom left,
			var(--colour-dark-lighter-20),
			var(--colour-dark)
		);
		margin: 3rem 1.5rem auto;
		padding: 1.5rem 1rem;
		width: 100%;
		text-align: center;
	}

	.content h1 {
		font-family: Montserrat;
		font-size: 1.802rem;
		font-weight: var(--font-weight-bold);
	}

	.content p {
		font-size: 1.25rem;
	}

	@media (min-width: 768px) {
		.content {
			width: 640px;
			margin-left: auto;
			margin-right: auto;
			padding-top: 0;
		}
	}

	@media (min-width: 1024px) {
		.content {
			width: 768px;
		}
	}

	@media (min-width: 1280px) {
		.content {
			width: 1024px;
		}
	}
</style>
