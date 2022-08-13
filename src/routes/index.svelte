<script>
	import '@fontsource/montserrat';
	import '@fontsource/hind';
</script>

<svelte:head>
	<title>SvelteKit Tooling Example Repo</title>
	<html lang="en-GB" />
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
	:global(html) {
		color: var(--colour-light);
	}

	:global(body) {
		margin: 0;
		font-family: Hind;
		font-weight: var(--font-weight-normal);
	}

	:global(:root) {
		--colour-theme: hsl(195 83% 38%); /* blue ncs */
		--colour-theme-lighter-20: hsl(195 83% 30%);
		--colour-light: hsl(42 100% 70%); /* orange yellow crayola */
		--colour-dark: hsl(195 83% 16%); /* midnight green eagle green */
		--colour-dark-lighter-20: hsl(195 83% 13%); /* black chocolate */

		--font-weight-normal: 400;
		--font-weight-bold: 700;
	}

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
