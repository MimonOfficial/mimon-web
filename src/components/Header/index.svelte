<script lang="ts">
  import Fa from 'svelte-fa'
  import {
    faTwitter,
    faDiscord,
    faMedium,
  } from '@fortawesome/free-brands-svg-icons'
</script>

<div class="background">
  <div class="wrap">
    <nav class="navbar">
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
    </nav>
  </div>
</div>

<style>
  .background {
    background-image: url('/assets/main_container.png');
    background-size: 100%;
  }
  .navbar {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 12px 12px;
    /* background-color: red; */
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

  @media screen and (max-width: 768px) {
    .logo-img {
      width: 150px;
    }
  }
</style>
