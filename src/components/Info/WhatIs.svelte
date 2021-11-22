<script>
</script>

<div class="background">
  <div class="wrap">
    <div class="struct">
      <div class="img-side">
        <img
          class="img-size"
          src="/assets/main_explain.png"
          alt="main_explain"
        />
      </div>
      <div class="text-side">
        <div class="text-title">What is MIMON?</div>
        <div class="text-paragraph">
          Mimon is a collection of 10,000 NFTs that is randomly generated using
          the Ethereum blockchain. Each Mimon, as a combination of various
          programmed attributes, is a medium of hope for those who seek to
          actualize their deepest desires. Mimon is a visual configuration of
          one’s subconscious dreams. Collect your own Mimon and realize your
          desires.
        </div>
      </div>
    </div>
  </div>
  <div>
    <img class="line" src="/assets/conponent_line.png" alt="line" />
  </div>
</div>

<style lang="scss">
  .background {
    background-color: $background-color;
  }
  .struct {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin: 0 40px;
    padding: 67px 0px;
  }
  .img-side {
    width: 35%;
  }

  .text-side {
    width: 50%;
  }

  .img-size {
    width: 100%;
  }

  .text-title {
    font-family: Comfortaa;
    font-size: 3.125rem;
    color: #211919;
    font-weight: bold;
    margin-bottom: 35px;
  }

  .text-paragraph {
    font-size: 1.5rem;
    color: #484848;
    font-weight: 300;
    line-height: 32px;
  }

  .line {
    width: 100%;
  }

  @media screen and (max-width: 768px) {
    .struct {
      flex-direction: column;
    }
    .img-side {
      width: 100%;
      margin-bottom: 10px;
    }

    .text-side {
      width: 100%;
    }
  }
</style>
