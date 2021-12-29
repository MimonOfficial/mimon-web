<script lang="ts">
  import Header from '@/components/Header/index.svelte'

  function alertFunc() {
    alert('Coming Soon!')
  }

  function openInNewTab(url: any) {
    const win: any = window.open(url, '_blank')
    win.focus()
  }
</script>

<div class="background">
  <video class="banner-video" src="/assets/banner-video.mp4" autoplay loop muted playsinline />
  <Header />
  <div class="wrap">
    <div class="struct">
      <div class="side">
        <div class="text">Fulfill Your</div>
        <div class="text">Desire, Mimon</div>
        <div class="button" on:click={() => openInNewTab('https://mint.mimons.io/')}>Mint Now!</div>
      </div>
    </div>
  </div>
</div>

<style>
  .banner-video {
    width: 100%;
    max-width: 100%;
    position: absolute;
    z-index: -99;
    min-width: 100%;
    min-height: 100%;
    object-fit: cover;
  }
  .struct {
    display: flex;
    margin: 0 40px;
    padding-top: 150px;
    padding-bottom: 95px;
  }

  .side {
    width: 40%;
  }

  .button {
    font-family: Comfortaa;
    display: flex;
    justify-content: center;
    align-items: center;
    width: 100px;
    background-color: #f096a7;
    color: white;
    font-weight: bold;
    padding: 15px;
    border-radius: 30px;
    cursor: pointer;
  }

  .text {
    font-family: Comfortaa;
    font-size: 3.125rem;
    color: #211919;
    font-weight: bold;
    margin-bottom: 30px;
  }
  .background {
    /* background-image: url('/assets/mainimg.jpg'); */
    height: 100vh;
    background-repeat: no-repeat;
    background-size: cover;
    background-position: center;
  }

  @media screen and (max-width: 920px) {
    .struct {
      display: flex;
      margin: 0 40px;
      padding-top: 50px;
      padding-bottom: 95px;
    }

    .text {
      font-family: Comfortaa;
      font-size: 2.125rem;
      color: #211919;
      font-weight: bold;
      margin-bottom: 30px;
    }
  }

  @media screen and (max-width: 820px) {
    .struct {
      display: flex;
      margin: 0 40px;
      padding-top: 20px;
      padding-bottom: 95px;
    }
  }

  @media screen and (max-width: 768px) {
    .struct {
      display: flex;
      margin: 0 40px;
      padding-top: 25px;
      padding-bottom: 95px;
    }

    .side {
      width: 100%;
      display: flex;
      align-items: center;
      justify-content: center;
      flex-direction: column;
    }

    .button {
      font-family: Comfortaa;
      display: flex;
      justify-content: center;
      align-items: center;
      width: 100px;
      background-color: #f096a7;
      color: white;
      font-weight: bold;
      padding: 15px;
      border-radius: 30px;
      cursor: pointer;
    }

    .text {
      font-family: Comfortaa;
      font-size: 2rem;
      color: #211919;
      font-weight: bold;
      margin-bottom: 10px;
    }
    .banner-video {
      width: 100%;
      max-width: 100%;
      position: absolute;
      z-index: -99;
      min-width: 100%;
      min-height: 118%;
      object-fit: cover;
    }
  }
</style>
