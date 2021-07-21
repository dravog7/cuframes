<script>
</script>

<div class="order-2 flex flex-col bg-black h-screen justify-around
            md:h-5/6 py-4 md:w-1/2">
    <div class="bg-cir-grad px-4 flex justify-center">
        <img class="h-v50" src="coverImage.png" alt="cover"/>
    </div>
    <div class="flex flex-col justify-around md:flex-row">
        <div class="stats"><h1>350+</h1><h3>COMPONENTS</h3></div>
        <div class="stats"><h1>50+</h1><h3>ICONS</h3></div>
        <div class="stats"><h1>200+</h1><h3>SCREENS</h3></div>
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
    @apply font-black text-4xl bg-gradient-to-t bg-clip-text text-transparent from-black to-white;
}
</style>