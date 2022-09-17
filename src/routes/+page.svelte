<script context="module">
import Hero from "../lib/components/hero.svelte";

	export const prerender = true;
</script>

<svelte:head>
	<title>Editions Marketplace</title>
</svelte:head>
<div>
  <Hero />
  <div class="hero min-h-screen bg-base-100">
	<div class="hero-content flex-col lg:flex-row">
	  <img src="https://placeimg.com/400/800/arch" class="max-w-sm rounded-lg shadow-2xl" style="place-items: centre stretch;" />
	  <div>
		<h1 class="text-5xl font-bold">Box Office News!</h1>
		<p class="py-6">Provident cupiditate voluptatem et in. Quaerat fugiat ut assumenda excepturi exercitationem quasi. In deleniti eaque aut repudiandae et a id nisi.</p>
		<button class="btn btn-primary">Get Started</button>
	  </div>
	</div>
  </div>
  <div class="hero min-h-screen bg-base-100">
	<div class="hero-content flex-col lg:flex-row-reverse">
	  <img src="https://placeimg.com/260/400/arch" class="max-w-sm rounded-lg shadow-2xl" />
	  <div>
		<h1 class="text-5xl font-bold">Box Office News!</h1>
		<p class="py-6">Provident cupiditate voluptatem et in. Quaerat fugiat ut assumenda excepturi exercitationem quasi. In deleniti eaque aut repudiandae et a id nisi.</p>
		<button class="btn btn-primary">Get Started</button>
	  </div>
	</div>
  </div>
</div>
