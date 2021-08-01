<script>
  import TitleCard from './components/TitleCard.svelte';
  import StatsCard from './components/StatsCard.svelte';
  import ProfileCard from './components/ProfileCard.svelte';
  import FooterCard from './components/FooterCard.svelte';
</script>

<div class="flex flex-col justify-between md:flex-row md:flex-wrap w-screen md:h-screen">
  <TitleCard/>
  <StatsCard/>
  <ProfileCard/>
  <FooterCard/>
</div>

<style global lang="postcss">
  @tailwind base;
  @tailwind components;
  @tailwind utilities;
</style>
