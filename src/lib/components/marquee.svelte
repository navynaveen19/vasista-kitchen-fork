<script>
	import Marquee from 'svelte-fast-marquee';
	let play = true;
</script>

<Marquee pauseOnHover={true} speed={40} {play}>
	<img src="./vasista_black.png" alt="Logo" class="sticky" />
	<p class="text-1xl md:text-3xl text-gray-700 font-bold text-center md:text-start">
		WE VASISTA READY TO DELIVERY A GOOD FOOD GOOD MOOD
	</p>
	<img src="./fooddelivery.png" alt="Logo" class="sticky" />
</Marquee>

<style>
	img {
		height: 100px;
		margin: 20px;
	}
</style>
