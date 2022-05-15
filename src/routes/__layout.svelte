<script lang="ts">
	import Header from '../lib/header.svelte';
    import '../app.css';
</script>

<svelte:head>
    <title>Malina Art</title>
</svelte:head>

<div class="app">
	<Header />
	<main>
		<slot />
	</main>
</div>

<style>

    
</style>