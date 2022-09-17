<script>
	import Nav from '$lib/components/nav.svelte';
	import Footer from '$lib/components/footer.svelte'
	import '../app.css';
</script>
<svelte:head>
	<link href="//db.onlinewebfonts.com/c/3618808eaeabd1dca88aec95a53fe2df?family=Butler" rel="stylesheet" type="text/css"/>
</svelte:head>

<div class="max-w-8xl mx-auto">
	<Nav />
	<slot />
	<div class="divider" />
	<Footer />
</div>

<style>
	:global(body) {
		overflow-x: hidden;
	}
</style>
