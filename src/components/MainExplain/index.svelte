<script lang="ts">
</script>

<div class="background">
  <div class="wrap">
    <div class="content-wrap">
      <div class="paragraph">
        <div class="paragraph-title"><b>What is MIMON?</b></div>
        <div class="paragraph-text">
          Mimon is a randomly generated collection of 10,000 NFTs based on the
          Ethereum blockchain. Each Mimon created through programming with the
          combination of more than 000 attributes is a manifestation of latent
          desires in our dreams, and all Mimons are very special. Confront the
          latent desires of your subconscious mind!
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
</div>

<style>
  .content-wrap {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin: 0 12px;
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
