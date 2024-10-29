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
	<title>BYXL</title>
</svelte:head>

<main class="grid text-center place-content-center bg-gray-100 text-gray-900 h-screen">
	{@render children?.()}
</main>
