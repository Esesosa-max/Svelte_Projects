<script>
  import img1 from "$lib/photo1.png";
  import img2 from "$lib/photo2.png";
  import img3 from "$lib/photo3.png";
</script>

<div class="md:row-4 lg:col-span-2">
  <div class="bg-white rounded-2xl 4 p-4">
    <p>Project (3)</p>
  </div>
  <div class="md:flex bg-white m-auto rounded-2xl shadow-2xl p-4 mt-5 ">
    <img src={img1} alt="" class="w-[320px] mr-3 rounded-2xl h-[274px]" />
    <div>
      <p class="text-black mb-3">#Svelte #TailwindCSS</p>
      <p class="text-2xl font-bold">Airbnb Clone</p>
      <p>
        Building the Frontend of Airbnb, It was very thrilling and Fun.
        Although, It was it was only frontend,The data was from API which made
        things more real. Sorting and Searching were tricky to begin with.
      </p>
      <div class="mt-5">
        <a
          class="bg-[#2F80ED] px-4 py-2 pointer md:w-[150px] w-[100px] rounded-xl text-white"
          href="https://windbnb-final.netlify.app/"
          target="_blank">Demo</a
        >
        <a
          href="https://github.com/Esesosa-max/Svelte_Projects"
          target="_blank"
          class="text-[#2F80ED] border-[#2F80ED] border-2 px-4 py-2 md:w-[150px] w-[100px] mt-2 rounded-xl bg-white"
          >Code</a
        >
      </div>
    </div>
  </div>
  <div class="md:flex bg-white m-auto rounded-2xl shadow-2xl p-4 mt-5">
    <img src={img2} alt="" class="w-[320px] mr-3 rounded-2xl h-[274px]" />
    <div>
      <p class="text-black mb-3">#Svelte #TailwindCSS</p>
      <p class="text-2xl font-bold">Gallery App</p>
      <p>
        A very Simple Minimalistic Instagram profile Application. It was a nice
        appentizer to bursh on CSS Grid with TailwindCSS
      </p>
      <div class="mt-5">
        <a
          target="_blank"
          href="https://svelte-gallery-tech-upfront.netlify.app/"
          class="bg-[#2F80ED] px-4 py-2  md:w-[150px] w-[100px] rounded-xl text-white"
          >Demo</a
        >
        <a
          href="https://github.com/Esesosa-max/Svelte_Projects"
          target="_blank"
          class="text-[#2F80ED] border-[#2F80ED] border-2 px-4 py-2 md:w-[150px] w-[100px] mt-2 rounded-xl bg-white"
          >Code</a
        >
      </div>
    </div>
  </div>
  <div class="md:flex bg-white m-auto rounded-2xl shadow-2xl p-4 mt-5">
    <img src={img3} alt="" class="w-[320px] mr-3 rounded-2xl h-[274px]" />
    <div>
      <p class="text-black mb-3">#Svelte #TailwindCSS</p>
      <p class="text-2xl font-bold">Suggestion Box</p>
      <p>
        A very Complex Application with Frontend and Backend. Orginally built
        for a university to cater student suggestion and ideas
      </p>
      <div class="mt-5">
      
      </div>
    </div>
  </div>
</div>
