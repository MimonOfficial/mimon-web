<script lang="ts">
</script>

<div class="wrap">
  <div class="content-wrap">
    <div class="paragraph">
      <div class="paragraph-title"><b>What is MIMON?</b></div>
      <div class="paragraph-text">
        Mimon is a collection of 10,000 NFTs that is randomly generated using 
        the Ethereum blockchain. Each Mimon, created as a combination of 
        various programmed attributes, is a actualization of your fantasies, 
        the latent desires discovered in dreams. It's time to come face to 
        face with those subconscious desires of yours.
      </div>
    </div>
    <div class="img-wrap">
      <img
        class="explain-img"
        src="/assets/main_explain.png"
        alt="main-explain"
      />
    </div>
  </div>
</div>

<style>
  .wrap {
    background: white;
  }
  .content-wrap {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin: 0 20px;
    padding-bottom: 100px;
  }
  .paragraph {
    width: 40%;
  }

  .img-wrap {
    width: 50%;
  }
  .explain-img {
    width: 100%;
  }

  .paragraph-title {
    font-size: 2.5rem;
    margin-bottom: 20px;
  }

  .paragraph-text {
    font-size: 1.2rem;
    letter-spacing: 0.5px;
    word-spacing: 5px;
    line-height: 35px;
  }

  @media screen and (max-width: 768px) {
    .content-wrap {
      display: flex;
      justify-content: space-between;
      align-items: center;
      margin: 0 20px;
      flex-direction: column;
      padding-bottom: 50px;
    }
    .paragraph {
      width: 100%;
    }

    .img-wrap {
      width: 100%;
    }
    .explain-img {
      width: 100%;
    }

    .paragraph-title {
      font-size: 2rem;
      margin-top: 20px;
      margin-bottom: 20px;
    }

    .paragraph-text {
      font-size: 1.2rem;
      letter-spacing: 0.5px;
      word-spacing: 5px;
      line-height: 35px;
    }
  }
</style>
