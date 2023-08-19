<script>
  import Blog from "./Blog.svelte";
  import Hobbies from "./Hobbies.svelte";
  import ProfileCard from "./ProfileCard.svelte";
  import Projects from "./Projects.svelte";
  import Skills from "./Skills.svelte";
  import Work from "./Work.svelte";
</script>

<!-- <div class="grid m-auto w-[1200px] grid-cols-3 gap-8 mt-4 grid-rows-2"> -->
<div class="app w-[90%] m-auto grid grid-cols-1 lg:grid-cols-3 lg:w-[1200px] mt-5  gap-8">
  <ProfileCard />
  <Skills />
  <Projects />
  <Work />
  <Hobbies />
  <Blog />
</div>

<!-- </div> -->
