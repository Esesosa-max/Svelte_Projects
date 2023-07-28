<script>
	import photo1 from '$lib/photo1.png';
	import photo2 from '$lib/photo2.png';
	import photo3 from '$lib/photo3.png';
	import photo_4 from '$lib/photo_4.png';
	import photo5 from '$lib/photo5.png';
	import photo6 from '$lib/photo6.png';
</script>

<div class=" m-auto grid grid-cols-3 justify-stretch gap-3 mt-3 " id="grid">
	<img src={photo1} class="col-span-1 w-full h-full rounded-lg" alt="" />
	<img src={photo2} class="col-span-2 w-full h-full  rounded-lg " />
	<img src={photo3} class="col-span-2 w-full h-full  rounded-lg" />
	<img src={photo_4} class="col-span-1 w-full h-full row-span-2  rounded-lg" />
	<img src={photo5} alt="" class="col-span-1 w-full h-full row-start-3  rounded-lg" />
	<img src={photo6} alt="" class="col-span-1 w-full h-full  rounded-lg" />
</div>

<style>
	#grid {
		max-width: 900px;
	}
	@media (max-width: 900px) {
		#grid {
			width: 90%;
		}
	}
</style>
