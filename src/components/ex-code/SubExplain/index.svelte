<script lang="ts">
</script>

<div class="wrap">
  <div class="content-wrap">
    <div class="paragraph-title-mobile"><b>MIMON’S STORY</b></div>
    <div class="img-wrap">
      <img
        class="explain-img"
        src="/assets/sub_explain_desktop.png"
        alt="main-explain"
      />
      <img
        class="explain-img-mobile"
        src="/assets/sub_explain_mobile.png"
        alt="main-explain_mobile"
      />
    </div>
    <div class="paragraph">
      <div class="paragraph-title"><b>MIMON’S STORY</b></div>
      <div class="paragraph-sub-title">
        <b>The Fusion of Art & Technology</b>
      </div>
      <div class="paragraph-text">
        The Mimong team received artistic inspiration from contemporary dream
        research, which states that dreams appear through brain algorithms as a
        combination of everyday memories and unconscious desires. As for
        technological inspiration, it has been influenced by generative art, an
        art that has been generated through programming.
      </div>
      <div class="paragraph-sub-title">
        <b>The blockchain property</b>
      </div>
      <div class="paragraph-text">
        Dreams are centralized in the individual human and vanishes from memory
        when the individual awakes. However, Mimong is decentralized through the
        Ethereum network and exists forever in the blockchain world.
      </div>
      <div class="paragraph-sub-title">
        <b>The Happiness Theory of Desire</b>
      </div>
      <div class="paragraph-text">
        We think that actualizing desire is a beautiful thing, and that which
        makes us happy. Therefore, we believe that collecting desires through
        the minting of Mimong, which in itself is at once a dream and a desire,
        can lead to happiness.
      </div>
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
    width: 85%;
  }

  .explain-img-mobile {
    display: none;
  }

  .paragraph-title-mobile {
    display: none;
  }

  .paragraph-title {
    font-size: 2.5rem;
    margin-bottom: 30px;
  }

  .paragraph-sub-title {
    font-size: 1.6rem;
    margin-bottom: 20px;
  }

  .paragraph-text {
    font-size: 1.2rem;
    letter-spacing: 0.5px;
    word-spacing: 5px;
    line-height: 35px;
    margin-bottom: 100px;
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
      display: none;
    }

    .paragraph-title {
      font-size: 2rem;
      margin-bottom: 30px;
      display: none;
    }

    .paragraph-sub-title {
      font-size: 1.4rem;
      margin-bottom: 20px;
    }

    .paragraph-text {
      font-size: 1.2rem;
      letter-spacing: 0.5px;
      word-spacing: 5px;
      line-height: 35px;
      margin-bottom: 50px;
    }
    .explain-img-mobile {
      width: 100%;
      display: block;
      margin-bottom: 30px;
    }
    .paragraph-title-mobile {
      font-size: 2.5rem;
      margin-bottom: 30px;
      display: block;
    }
  }
</style>
