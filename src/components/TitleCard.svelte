<script>

</script>

<style lang="postcss">
  .button {
    @apply flex mx-4 md:mx-2 p-4 px-8 md:px-16 justify-center rounded-xl;
  }
  .button > img {
    @apply h-8 mr-2;
  }
  .button > span {
    @apply font-bold;
  }
</style>

<div class="order-1 md:ml-24 flex flex-col justify-around py-2 px-1 md:h-5/6
            md:w-1/3 md:h-auto">
  <div class="flex flex-col justify-around px-8" style="flex:2;">
    <div>
      <img class="h-14" src="Logo.png" alt="logo" />
    </div>
    <div>
      <h1 class="font-bold text-5xl md:text-7xl py-1">cutframe</h1>
      <h2 class="font-bold text-gray-400 text-6xl">wireframe kit</h2>
    </div>
    <p class="md:text-2xl font-light text-gray-400 ">
      An open source wireframe kit for designers which include 350+ components and
      200+ available in both light and dark mode.
    </p>
  </div>
  <div class="flex flex-col  flex-1 
              md:flex-row md:content-center md:flex-initial">
    <a
      href="https://ko200.github.io/cuframes/"
      class="button bg-black text-white visited:text-white">
      <img src="./figma.png" alt="figma" />
      <span class="text-xl">Get it now</span>
    </a>
    <a
      href="https://www.buymeacoffee.com/vishnukoux"
      class="button bg-gray-200 text-black visited:text-black">
      <img src="./Coffee.png" alt="coffee" />
      <span class="text-xl">Buy me a coffee</span>
    </a>
  </div>
</div>
