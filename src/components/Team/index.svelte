<script lang="ts">
  import Fa from 'svelte-fa'
  import { faTwitter } from '@fortawesome/free-brands-svg-icons'
</script>

<div class="background">
  <div class="wrap">
    <div class="struct">
      <div class="title-side">
        <div class="title">TEAM</div>
      </div>
    </div>
  </div>
  <div class="wrap">
    <div class="struct-content">
      <div class="box-side">
        <div class="box">
          <div class="box-img">
            <img class="img-size" src="/assets/team1.png" alt="team" />
          </div>
          <div class="box-content">
            <div class="box-title-section">
              <div class="box-title">Patxi</div>
              <div class="box-icon">
                <a href="https://twitter.com/MIMON_OFFICIAL" target="_blank"
                  ><Fa icon={faTwitter} size="2x" /></a
                >
              </div>
            </div>
            <div class="box-paragraph">
              Untill the day Bitcoin becomes the world number one surrency.
            </div>
          </div>
        </div>
        <div class="box">
          <div class="box-img">
            <img class="img-size" src="/assets/team1.png" alt="team" />
          </div>
          <div class="box-content">
            <div class="box-title-section">
              <div class="box-title">Linling</div>
              <div class="box-icon" />
            </div>
            <div class="box-paragraph">
              If a pill that keeps young forever, this guy will sell everything
              that has even all of bitcoin just to acquire some.
            </div>
          </div>
        </div>
        <div class="box">
          <div class="box-img">
            <img class="img-size" src="/assets/team1.png" alt="team" />
          </div>
          <div class="box-content">
            <div class="box-title-section">
              <div class="box-title">Elixir</div>
              <div class="box-icon" />
            </div>
            <div class="box-paragraph">
              Likes cats, developed a blockchain called popcateum.
            </div>
          </div>
        </div>
        <div class="box">
          <div class="box-img">
            <img class="img-size" src="/assets/team1.png" alt="team" />
          </div>
          <div class="box-content">
            <div class="box-title-section">
              <div class="box-title">Scale</div>
              <div class="box-icon" />
            </div>
            <div class="box-paragraph">
              This person thinks own brain is being controlled by the brain in
              the vat. Absolute mental this guy.
            </div>
          </div>
        </div>
        <div class="box">
          <div class="box-img">
            <img class="img-size" src="/assets/team1.png" alt="team" />
          </div>
          <div class="box-content">
            <div class="box-title-section">
              <div class="box-title">Means</div>
              <div class="box-icon" />
            </div>
            <div class="box-paragraph">
              Wants to float in the Mediterranean sea and loves seafood.
            </div>
          </div>
        </div>
        <div class="box">
          <div class="box-img">
            <img class="img-size" src="/assets/team1.png" alt="team" />
          </div>
          <div class="box-content">
            <div class="box-title-section">
              <div class="box-title">Songul</div>
              <div class="box-icon" />
            </div>
            <div class="box-paragraph">
              Going to run a guest house on an island. All Mimon holders are
              entitled for free access!
            </div>
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
    background: #fbdee5;
  }
  .struct {
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    align-items: center;
    margin: 0 40px;
    padding-top: 121px;
    padding-bottom: 34px;
  }

  .struct-content {
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    margin: 0 40px;
    align-items: center;
    padding-bottom: 170px;
  }

  .title-side {
    width: 100%;
    display: flex;
    justify-content: start;
    margin-bottom: 34px;
  }

  .title {
    font-family: Comfortaa;
    font-size: 3.125rem;
    color: #211919;
    font-weight: bold;
  }

  .box-side {
    width: 100%;
    display: flex;
    justify-content: space-between;
    align-items: center;
    flex-wrap: wrap;
  }

  .box {
    width: 31%;
    height: 530px;
    border: 3px solid #211919;
    box-sizing: border-box;
    box-shadow: 15px 15px 20px 5px rgba(0, 0, 0, 0.25);
    background: #fff6f8;
    margin-bottom: 50px;
  }

  .box-content {
    padding: 25px;
  }

  .box-title-section {
    display: flex;
    justify-content: space-between;
    /* align-items: center; */
  }

  .box-title {
    font-family: Comfortaa;
    font-size: 1.75rem;
    color: #211919;
    font-weight: bold;
    margin-bottom: 24px;
  }
  .box-paragraph {
    font-family: Sansation Light;
    font-size: 1.125rem;
    color: #484848;
    font-weight: 300;
  }

  .img-size {
    width: 100%;
    background-color: lightgray;
  }

  .line {
    width: 100%;
  }

  @media screen and (max-width: 768px) {
    .box-side {
      width: 100%;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
    }
    .box {
      width: 100%;
      height: auto;
      border: 3px solid #211919;
      box-sizing: border-box;
      box-shadow: none;
      background: #fff6f8;
      margin-right: 0px;
      margin-bottom: 30px;
    }
  }
</style>
