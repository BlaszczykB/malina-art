<script lang="ts">
	import Header from '../lib/header.svelte';
	import Footer from '../lib/footer.svelte';
    import '../app.css';
</script>

<svelte:head>
    <title>Malina Art</title>
	<meta property="og:title" content="Malina Art - Studio Makijażu">
	<meta property="og:type" content="website" />
	<meta property="og:description" content="Piękne makijaże robione z pasji">
	<meta property="og:image" content="http://euro-travel-example.com/thumbnail.jpg">
	<meta property="og:url" content="http://euro-travel-example.com/index.htm">
	<meta property="og:site_name" content="Malina Art - Studio Makijażu">
	<!-- <meta name="twitter:card" content="summary_large_image"> -->
</svelte:head>

<div class="app">
	<Header />
	<main>
		<slot />
	</main>
	<!-- <Footer/> -->
</div>

<style>

    
</style>