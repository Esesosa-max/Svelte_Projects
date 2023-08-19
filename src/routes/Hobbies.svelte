<script>
  import img1 from "$lib/img4.jpg";
  import img2 from "$lib/img5.jpg";
  import img3 from "$lib/img6.jpg";
</script>

<div class="bg-white p-4 lg:h-[1100px] rounded-2xl">
  <p class="text-black text-2xl mb-2 font-bold">Hobbies</p>
  <div class="hobby pt-4">
    <img src={img1} class="rounded-2xl" />
    <p class="text-black text-xl font-bold">Playing Games</p>
    <p>Playing Soccer Will Always be the Best Playstation Game</p>
  </div>
  <div class="hobby pt-4">
    <img src={img2} class="rounded-2xl" alt="" />
    <p class="text-black font-bold text-xl ">Playing Guitar</p>
    <p>
      Music helps me to relax and calm down. My Guitar Skills are not Great but
      I won't say I'm a Beginner!
    </p>
  </div>
  <div class="hobby pt-4">
    <img src={img3} class="rounded-2xl" alt="" />
    <p class="text-black font-bold text-xl">Playing Chess</p>
    <p>
      Ahh, This help me to Focus and I am Currently rated 1100 in 10 Minute
      Chess
    </p>
  </div>
</div>
