<script lang="ts">
  import Fa from 'svelte-fa'
  import { faTwitter } from '@fortawesome/free-brands-svg-icons'

  export let image: string
  export let name: string
  export let explain: string
  export let twitter: string
  export let position: string
</script>

<div class="box">
  <div class="box-img">
    <img class="img-size" src={image} alt="team" />
  </div>
  <div class="box-content">
    <div class="box-title-section">
      <div class="box-title">{name}</div>
      <div class="box-icon">
        <a href={twitter} target="_blank"><Fa icon={faTwitter} size="2x" /></a>
      </div>
    </div>
    <div class="box-position">
      {position}
    </div>
    <div class="box-paragraph">
      {explain}
    </div>
  </div>
</div>

<style lang="scss">
  .box {
    width: 31%;
    height: 550px;
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

  .box-position {
    font-family: Comfortaa;
    font-size: 1.2rem;
    color: #484848;
    font-weight: 300;
    font-weight: bold;
    /* margin-bottom: 20px; */
  }

  .img-size {
    width: 100%;
    background-color: lightgray;
  }

  @media screen and (max-width: 768px) {
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
