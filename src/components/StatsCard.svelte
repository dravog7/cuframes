<script>
</script>

<div class="order-2 flex flex-col md:py-1 md:pb-4 py-32 bg-black justify-around
            md:h-auto py-4 md:w-1/2">
    <div class="bg-cir-grad px-4 flex justify-center">
        <img class="h-v50" src="./coverImage.png" alt="cover"/>
    </div>
    <div class="flex flex-col justify-around md:flex-row">
    <div class="stats md:mt-0 mt-12"><h1>350+</h1><h3 class="text-xl text-gray-500 mt-4" style="letter-spacing:5px" >COMPONENTS</h3></div>
        <div class="stats md:mt-0 mt-9"><h1>50+</h1><h3 class="text-gray-500 text-xl mt-4"style="letter-spacing:5px">ICONS</h3></div>
        <div class="stats md:mt-0 mt-9"><h1>200+</h1><h3 class="text-gray-500 text-xl mt-4" style="letter-spacing:5px">SCREENS</h3></div>
    </div>
</div>

<style lang="postcss">
.bg-cir-grad {
    background-image: radial-gradient(rgb(75, 85, 99),#000 60%,#000);
}
.stats {
    @apply flex flex-col text-center;
}
.stats > h1 {
    @apply font-black md:text-6xl text-5xl bg-gradient-to-t bg-clip-text text-transparent from-black to-white;
}
</style>