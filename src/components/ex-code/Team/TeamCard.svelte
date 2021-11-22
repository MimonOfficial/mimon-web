<script lang="ts">
  import Fa from 'svelte-fa'
  import { faTwitter } from '@fortawesome/free-brands-svg-icons'

  export let image: string
  export let name: string
  export let explain: string
  export let twitter: string
</script>

<div class="team-box">
  <img class="team-img" src={image} alt="team" />
  <div class="team-explain-section">
    <div class="team-explain-header">
      <div class="team-name">{name}</div>
      <div class="team-icon">
        <a href={twitter} target="_blank"><Fa icon={faTwitter} size="lg" /></a>
      </div>
    </div>
    <div class="team-explain-content">
      {explain}
    </div>
  </div>
</div>

<style>
  .team-box {
    width: 30%;
    border: 0.5px solid lightgray;
    border-radius: 30px;
    box-sizing: border-box;
    box-shadow: 0px 3px 3px lightgray;
    margin-bottom: 50px;
  }

  .team-img {
    width: 100%;
    background-color: lightgray;
    border-radius: 28px 28px 0px 0px;
    box-sizing: border-box;
  }

  .team-explain-section {
    padding: 30px;
  }

  .team-explain-header {
    display: flex;
    margin-bottom: 25px;
    box-sizing: border-box;
    justify-content: space-between;
    font-family: 'Source Code Pro', monospace;
  }

  .team-explain-content {
    font-size: 1.1rem;
    min-height: 120px;
    font-family: 'Source Code Pro', monospace;
    line-height: 25px;
  }

  .team-name {
    font-size: 1.5rem;
  }

  @media screen and (max-width: 768px) {
    .team-box {
      width: 100%;
      border: 0.5px solid lightgray;
      border-radius: 30px;
      box-sizing: border-box;
      box-shadow: 0px 3px 3px lightgray;
      margin-bottom: 50px;
    }
  }
</style>
