<script lang="ts">
	import '../app.css';
	import favicon from '$lib/assets/favicon.svg';
	
	let { children } = $props();
</script>

<svelte:head>
	<link rel="icon" href={favicon} />
</svelte:head>

<nav class="bg-white border-gray-200 dark:bg-gray-900">
	<a href="/">Home</a>
	<a href="/about">About</a>
</nav>

{@render children?.()}

<p></p>