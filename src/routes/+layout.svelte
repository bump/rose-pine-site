<script>
	import Banner from "./banner.svelte";
	import Header from "./header.svelte";
	import "../app.css";
</script>

<a href="#content" class="sr-only">Skip to main content</a>

<Header />

<div class="min-h-content bg-gradient-to-br from-surface to-base pt-header">
	<Banner />
	<div class="p-6">
		<main id="content" class="mx-auto max-w-content">
			<slot />
		</main>
	</div>
</div>
