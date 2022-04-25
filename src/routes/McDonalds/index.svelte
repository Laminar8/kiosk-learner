<script context="module" lang="ts">
	export const prerender = true;
</script>

<svelte:head>
	<title>McDonalds</title>
</svelte:head>

<section>
	<h1>
		<div class="welcome">
			<picture>
				<source srcset="McDonalds/ricottaCheese.png" alt="ricottaCheese" />
				<img src="McDonalds/ricottaCheese.png" alt="ricottaCheese" />
			</picture>
		</div>

		to your new<br />SvelteKit app
	</h1>

	<h2>
		try editing <strong>src/routes/index.svelte</strong>
	</h2>
</section>