<script>
	import '../app.postcss';
	import Nav from '$lib/components/Nav.svelte';
	import Footer from '$lib/components/Footer.svelte';
</script>

<svelte:head>
	<title>WAG RFN Finder</title>
</svelte:head>

<Nav />

<div class="container max-w-3xl mx-auto px-4 sm:px-6 lg:px-8 mb-10">
	<slot />
</div>

<Footer />
