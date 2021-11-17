<script lang="ts">
  import Fa from 'svelte-fa'
  import { faTwitter, faDiscord } from '@fortawesome/free-brands-svg-icons'
</script>

<div class="wrap">
  <div class="footer-wrap">
    <div class="left-section">
      <div class="logo-part">
        <img class="logo-img" src="/assets/logo.png" alt="mainlogo" />
      </div>
      <div class="explain-part">
        <div>ⓒ2021 DE3SFUL LABS, All rights reserved.</div>
      </div>
    </div>
    <div class="right-section">
      <ul class="nav-icon-wrap">
        <li>
          <a href="https://twitter.com/MIMON_OFFICIAL" target="_blank"
            ><Fa icon={faTwitter} size="2x" /></a
          >
        </li>
        <li>
          <a href="https://discord.com/invite/t4sAvpTT" target="_blank"
            ><Fa icon={faDiscord} size="2x" /></a
          >
        </li>
      </ul>
    </div>
  </div>
  <!-- <nav class="navbar">
    <a href="/">
      <img class="logo-img" src="/assets/logo.png" alt="mainlogo" />
    </a>
    <ul class="nav-icon-wrap">
      <li>
        <a href="https://twitter.com/MIMON_OFFICIAL" target="_blank"
          ><Fa icon={faTwitter} size="2x" /></a
        >
      </li>
      <li>
        <a href="https://discord.com/invite/t4sAvpTT" target="_blank"
          ><Fa icon={faDiscord} size="2x" /></a
        >
      </li>
    </ul>
  </nav> -->
</div>

<style>
  .footer-wrap {
    display: flex;
    justify-content: space-between;
    margin: 0 20px;
    margin-bottom: 50px;
  }
  .left-section {
    display: flex;
    flex-direction: column;
  }

  .logo-part {
    margin-bottom: 20px;
  }
  .explain-part {
    font-family: 'Source Code Pro', monospace;
    color: gray;
    font-size: 1rem;
  }

  .logo-img {
    width: 150px;
  }

  .nav-icon-wrap {
    display: flex;
  }

  li {
    padding: 10px;
  }

  a {
    text-decoration: none;
    color: #eb8f9b;
  }

  @media screen and (max-width: 768px) {
    .footer-wrap {
      display: flex;
      justify-content: space-between;
      margin: 0 20px;
      margin-bottom: 50px;
      flex-direction: column;
    }

    .explain-part {
      font-family: 'Source Code Pro', monospace;
      color: gray;
      margin-bottom: 50px;
    }
    .nav-icon-wrap {
      display: flex;
      justify-content: center;
    }

    .logo-part {
      display: flex;
      justify-content: center;
      margin-bottom: 20px;
    }
    .logo-img {
      width: 50%;
    }
  }
</style>
