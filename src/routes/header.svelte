<script>
	import profilePhoto from '$lib/profilePhoto.png';
</script>

<header class="flex justify-center mt-10">
	<div class="">
		<div class="flex flex-col justify-center">
			<img src={profilePhoto} alt="" class=" m-auto text-center w-[160px] rounded-lg" />
			<h4 class="text-center text-xl text-black font-bold">Rodney Cotton</h4>
			<p class="text-center">Heiskinki Finland</p>
		</div>
		<div class="tab-container mt-3 flex justify-between w-[300px] ">
			<div class="tab bg-slate-300 px-4 py-1 rounded-lg">
				<h4>100</h4>
				<p>Posts</p>
			</div>
			<div class="tab bg-slate-300 px-2 py-1 rounded-lg">
				<h4>2,243</h4>
				<p>Followers</p>
			</div>
			<div class="tab bg-slate-300 px-2 py-1 rounded-lg">
				<h4>1432</h4>
				<p>Following</p>
			</div>
		</div>
	</div>
</header>
