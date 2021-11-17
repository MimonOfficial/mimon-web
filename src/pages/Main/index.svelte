<script lang="ts">
  import Header from '@/components/Header/index.svelte'
  import Banner from '@/components/Banner/index.svelte'
  import MainExplain from '@/components/MainExplain/index.svelte'
  import SubExplain from '@/components/SubExplain/index.svelte'
  import Gallery from '@/components/Gallery/index.svelte'
  import Team from '@/components/Team/index.svelte'
</script>

<div class="background-banner">
  <Header />
  <Banner />
</div>
<div class="background-explain">
  <MainExplain />
  <SubExplain />
</div>
<Gallery />
<Team />

<style>
  .background-banner {
    background-image: url('/assets/main_container.png');
    background-size: 100% 100%;
    background-repeat: no-repeat;
  }
  .background-explain {
    background-image: url('/assets/background_icons.png');
    background-size: 100% 100%;
    background-repeat: no-repeat;
  }
</style>
