<script lang="ts">
</script>

<div class="background">
  <div class="wrap">
    <div class="banner">
      <div class="banner-content">
        <div class="banner-title"><b>Fultill Your Desire, <br />Mimon</b></div>
        <div class="banner-text">
          In Dream, Face to face the <br />latent beautiful desires
        </div>
        <div class="banner-btn"><b>MINT NOW !!!</b></div>
      </div>
      <div class="banner-img-wrap">
        <img class="banner-img" src="/assets/main_mimon.png" alt="banner-img" />
      </div>
    </div>
  </div>
</div>

<style>
  .background {
    background-image: url('/assets/main_container.png');
    background-size: 100% 100%;
    background-repeat: no-repeat;
  }
  .banner {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin: 0 12px;
  }

  .banner-content {
    width: 50%;
    display: flex;
    flex-direction: column;
  }

  .banner-img-wrap {
    width: 50%;
  }

  .banner-img {
    width: 100%;
  }

  .banner-title {
    font-size: 2.5rem;
    margin-bottom: 20px;
  }

  .banner-text {
    font-size: 1rem;
    margin-bottom: 20px;
  }
  .banner-btn {
    display: flex;
    width: 50%;
    height: 50px;
    border-radius: 50px;
    background-color: #CDB4DB;
    box-sizing: border-box;
    cursor: pointer;
    padding: 10px;
    justify-content: center;
    align-items: center;
    font-size: 1.3rem;
  }

  @media screen and (max-width: 768px) {
    .banner {
      display: flex;
      justify-content: space-between;
      align-items: center;
      margin: 0 20px;
      flex-direction: column;
    }
    .banner-content {
      width: 100%;
      display: flex;
      flex-direction: column;
    }

    .banner-img-wrap {
      width: 100%;
    }

    .banner-title {
      font-size: 2rem;
      margin-top: 20px;
      margin-bottom: 20px;
    }

    .banner-text {
      font-size: 1.2rem;
      margin-bottom: 20px;
    }

    .banner-btn {
      display: flex;
      width: 70%;
      height: 50px;
      border-radius: 50px;
      background-color: #CDB4DB;
      box-sizing: border-box;
      cursor: pointer;
      padding: 10px;
      justify-content: center;
      align-items: center;
      font-size: 1.3rem;
    }
  }
</style>
