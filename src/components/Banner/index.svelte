<script>
  import Header from '@/components/Header/index.svelte'

  function alertFunc() {
    alert('Coming Soon!')
  }
</script>

<div class="background">
  <Header />
  <div class="wrap">
    <div class="struct">
      <div class="side">
        <div class="text">Fulfill Your</div>
        <div class="text">Desire, Mimon</div>
        <div class="button" on:click={alertFunc}>DREAM</div>
      </div>
    </div>
  </div>
</div>

<style>
  .struct {
    display: flex;
    margin: 0 40px;
    padding-top: 385px;
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
    background-image: url('/assets/mainimg.jpg');
    height: 100vh;
    background-repeat: no-repeat;
    background-size: cover;
    background-position: center;
  }

  @media screen and (max-width: 768px) {
    .struct {
      display: flex;
      margin: 0 40px;
      padding-top: 45px;
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
  }
</style>
