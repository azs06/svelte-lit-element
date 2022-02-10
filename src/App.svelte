<script>
	import { title, header } from '../styles/index';
	import Component from './Component.svelte';
	export let name = 'Soikat';
</script>

<main>
	<h1 style={title.cssText}>Hello {name}!</h1>
	<Component />
</main>

<style>
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}

	/* 	
	h1 {
		color: #ff3e00;
		text-transform: uppercase;
		font-size: 4em;
		font-weight: 100;
	} 
	*/

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>