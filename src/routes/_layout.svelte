<script>
	import Nav from '../components/Nav.svelte';
	// import Foot from '../components/Footer.svelte';
	import { onMount } from "svelte"
	export let segment;

	onMount(function(){
		setTimeout(()=>{
			document.querySelector("div#preloader").style.visibility = "hidden"
		}, 200)
	})
</script>

<style>
	
</style>

<div id="preloader">
	<div class="jumper">
		<div></div>
		<div></div>
		<div></div>
	</div>
</div> 

<Nav {segment}/>

<main>
	<slot></slot>
</main>