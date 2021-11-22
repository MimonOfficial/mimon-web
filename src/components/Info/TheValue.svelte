<script>
</script>

<div class="background">
  <div class="wrap">
    <div class="struct">
      <div class="title-side">
        <div class="title">The value of MIMON</div>
      </div>
      <div class="box-side">
        <div class="box">
          <div class="box-img-section">
            <img class="img-size" src="/assets/value_img_1.png" alt="boximg" />
          </div>
          <div class="box-title-section">Art & Technology</div>
          <div class="box-paragraph-section">
            The Mimon team received artistic inspiration from contemporary dream
            research, which states that dreams appear through brain algorithms
            as a combination of everyday memories and unconscious desires. As
            for technological inspiration, it has been influenced by generative
            art, an art that has been generated through programming.
          </div>
        </div>
        <div class="box">
          <div class="box-img-section">
            <img class="img-size" src="/assets/value_img_2.png" alt="boximg" />
          </div>
          <div class="box-title-section">Blockchain Property</div>
          <div class="box-paragraph-section">
            Dreams are centralized in the individual human and vanishes from
            memory when the individual awakes. However, Mimon is decentralized
            through the Ethereum network and exists forever in the blockchain
            world.
          </div>
        </div>
        <div class="box">
          <div class="box-img-section">
            <img class="img-size" src="/assets/value_img_3.png" alt="boximg" />
          </div>
          <div class="box-title-section">Authentic Happiness</div>
          <div class="box-paragraph-section">
            We think that actualizing desire is a beautiful thing, and that
            which makes us happy. Therefore, we believe that collecting desires
            through the minting of Mimon, which in itself is at once a dream and
            a desire, can lead to happiness.
          </div>
        </div>
      </div>
    </div>
  </div>
  <div>
    <img class="line" src="/assets/component_line_2.png" alt="line" />
  </div>
</div>

<style lang="scss">
  .background {
    background: #fff9fa;
  }
  .struct {
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    align-items: center;
    margin: 0 40px;
    padding-top: 85px;
    padding-bottom: 95px;
  }

  .title-side {
    width: 100%;
    display: flex;
    justify-content: center;
    margin-bottom: 78px;
  }

  .box-side {
    width: 100%;
    display: flex;
    justify-content: space-between;
    align-items: center;
  }

  .title {
    font-family: Comfortaa;
    font-size: 3.125rem;
    color: #211919;
    font-weight: bold;
  }

  .box {
    display: flex;
    flex-direction: column;
    /* justify-content: center; */
    align-items: center;
    width: 30%;
    height: 670px;
    padding: 30px 34px;
    border: 3px solid #211919;
    box-sizing: border-box;
    box-shadow: 15px 15px 20px 5px rgba(0, 0, 0, 0.25);
    background: #fff6f8;
  }

  .box-img-section {
    width: 70%;
    margin-top: 16px;
    margin-bottom: 36px;
  }

  .box-title-section {
    font-family: Comfortaa;
    font-size: 1.875rem;
    color: #211919;
    font-weight: bold;
    margin-bottom: 27px;
  }

  .box-paragraph-section {
    font-family: Sansation Light;
    font-size: 1.125rem;
    color: #484848;
    font-weight: 300;
    line-height: 28px;
  }

  .img-size {
    width: 100%;
  }

  .line {
    width: 100%;
  }

  @media screen and (max-width: 768px) {
    .struct {
      flex-direction: column;
    }
    .box-side {
      width: 100%;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
    }

    .box {
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      width: 100%;
      height: auto;
      padding: 30px 34px;
      border: 3px solid #211919;
      box-sizing: border-box;
      box-shadow: 15px 15px 20px 5px rgba(0, 0, 0, 0.25);
      background: #fff6f8;
      margin-bottom: 36px;
    }
  }
</style>
