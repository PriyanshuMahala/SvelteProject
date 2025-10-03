<script lang="ts">
	import '../app.css';
	import favicon from '$lib/assets/favicon.svg';
	
	let { children } = $props();
</script>

<svelte:head>
	<link rel="icon" href={favicon} />
</svelte:head>

<nav class="flex space-x-3 py-3" >
	<a class="hover:text-gray-200 transition duration-200" href="/">Home</a>
	<a class="hover:text-gray-200 transition duration-200" href="/about">About</a>
</nav>

{@render children?.()}

<p></p>