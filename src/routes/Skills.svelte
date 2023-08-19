<div class="bg-white row-span-1 rounded-2xl p-4 lg:h-[250px]  shadow-2xl">
  <p class="text-lg font-bold">FRONTEND</p>

  <div class="flex items-center justify-between p-1">
    <p>CSS</p>
    <progress max="100" value="70">80%</progress>
  </div>
  <div class="flex items-center justify-between p-1">
    <p>React</p>
    <progress max="100" value="68">80%</progress>
  </div>
  <div class="flex items-center justify-between p-1  shadow-2xl">
    <p>Javascript</p>
    <progress max="100" value="90">80%</progress>
  </div>
  <div class="flex items-center justify-between p-1">
    <p>Firebase</p>
    <progress max="100" value="71">80%</progress>
  </div>
  <div class="flex items-center justify-between p-1">
    <p>TailwindCSS</p>
    <progress max="100" value="71">80%</progress>
  </div>
</div>
<div class="bg-white lg:h-[150px]  rounded-2xl p-4">
  <p class="text-lg font-bold">DESIGN</p>

  <div class="flex items-center justify-between p-1">
    <p>Figma</p>
    <progress max="100" value="30">80%</progress>
  </div>
  <div class="flex items-center justify-between p-1">
    <p>Photoshop</p>
    <progress max="100" value="38">80%</progress>
  </div>
</div>
<div class="bg-white lg:h-[150px] rounded-2xl p-4  shadow-2xl">
  <p class="text-lg font-bold">Content Creation</p>

  <div class="flex items-center justify-between p-1">
    <p>92+ Videos</p>
    <progress max="100" value="70">80%</progress>
  </div>
  <div class="flex items-center justify-between p-1">
    <p>20+ Articles</p>
    <progress max="100" value="68">80%</progress>
  </div>
</div>

<style>
  progress[value] {
    --color: #2f80ed;
    /* the progress color */
    --background: lightgrey; /* the background color */

    -webkit-appearance: none;
    -moz-appearance: none;
    appearance: none;
    border: none;
    width: 200px;
    height: 11px;
    margin: 0 10px;
    border-radius: 10em;
    background: var(--background);
  }
  progress[value]::-webkit-progress-bar {
    border-radius: 10em;
    background: var(--background);
  }
  progress[value]::-webkit-progress-value {
    border-radius: 10em;
    background: var(--color);
  }
  progress[value]::-moz-progress-bar {
    border-radius: 10em;
    background: var(--color);
  }
</style>
