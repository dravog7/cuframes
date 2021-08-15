<script>

</script>

<style lang="postcss">
  .button {
    @apply flex mx-4 md:mx-2 p-4 px-1 md:px-16 justify-center rounded-xl;
  }
  .button > img {
    @apply h-6 mr-2;
  }
  .button > span {
    @apply font-semibold;
  }
</style>

<div class="order-1 md:ml-16 flex flex-col pt-20 pb-20 md:pb-2 md:h-5/6
            md:w-1/3 ">
  <div class="flex flex-col justify-around px-8" style="flex:2;">
    <div>
      <img class=" h-12 md:mt-4 md:h-14" src="Logo.png" alt="logo" />
    </div>
    <div class="md:mt-8">
      <h1 class="font-bold text-6xl md:text-7xl pt-4">cutframe</h1>
      <h2 class="font-bold text-gray-400  pt-2 text-4xl md:text-6xl">wireframe kit</h2>
      <p class="text-xl md:text-2xl  pt-8 md:pt-12 font-light text-gray-400 ">
        An open source wireframe kit for quick design and prototyping your idea. Which includes 250+ components , 200+ screens and 170+ icons exclusively for mobile devices available in both light and dark mode.

      </p>
    </div>
    
  </div>
  <div class="md:mx-6 mx-3 mt-12  md:mt-24 md:pt-1   flex-1 
              md:flex-row md:content-center md:flex-initial">
    <a
      href="https://ko200.github.io/cuframes/"
      class="button bg-black mt-15 text-white visited:text-white">
      <img src="./figma.png" height="100px" alt="figma" />
      <span class="text-xl">Get it now</span>
    </a>
    <div class="py-2 md:py-3">

    </div>
    <a
      href="https://www.buymeacoffee.com/vishnukoux"
      class="button bg-gray-200 mt-19 md:pt-1 text-black visited:text-black">
      <img src="./Coffee.png" alt="coffee" />
      <span class="text-xl">Buy me a coffee</span>
    </a>
  </div>
</div>
