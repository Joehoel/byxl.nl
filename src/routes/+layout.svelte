<script>
	import '../app.postcss';
	/**
	 * @typedef {Object} Props
	 * @property {import('svelte').Snippet} [children]
	 */

	/** @type {Props} */
	let { children } = $props();
</script>

<svelte:head>
	<script
		defer
		src="https://analytics.longux.xyz/script.js"
		data-website-id="7a706958-da21-49ef-8952-5502c88a6762"
	></script>
	<title>BYXL</title>
</svelte:head>

<main class="grid text-center place-content-center bg-gray-100 text-gray-900 h-screen">
	{@render children?.()}
</main>
