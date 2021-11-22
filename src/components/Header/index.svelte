<script lang="ts">
  import { sns } from '../../links/index'
  import Fa from 'svelte-fa'
  import {
    faTwitter,
    faDiscord,
    faMedium,
    faInstagram,
  } from '@fortawesome/free-brands-svg-icons'
  import { faBars } from '@fortawesome/free-solid-svg-icons'

  function alertFunc() {
    alert('Coming Soon!')
  }
</script>

<div class="wrap">
  <div class="navbar">
    <div class="logo">
      <a href="/">
        <img class="logo-img" src="/assets/logo.png" alt="mainlogo" />
      </a>
    </div>
    <div class="menu-button">
      <Fa icon={faBars} size="2x" />
    </div>

    <div class="right-side">
      <div class="icons">
        <a class="icon-link" href={sns.discord} target="_blank">
          <div class="icon-button"><Fa icon={faDiscord} size="1x" /></div>
        </a>
        <div class="icon-link" on:click={alertFunc} target="_blank">
          <div class="icon-button">
            <img
              class="opensea-icon"
              src="/assets/opensea_icon.svg"
              alt="openseaicon"
            />
          </div>
        </div>
        <a class="icon-link" href={sns.twitter} target="_blank">
          <div class="icon-button"><Fa icon={faTwitter} size="1x" /></div>
        </a>
        <a class="icon-link" href={sns.medium} target="_blank">
          <div class="icon-button"><Fa icon={faMedium} size="1x" /></div>
        </a>
        <a class="icon-link" href={sns.instagram} target="_blank">
          <div class="icon-button"><Fa icon={faInstagram} size="1x" /></div>
        </a>
      </div>
      <div class="connect-button" on:click={alertFunc}>Wallet Conect</div>
    </div>
  </div>
</div>

<style lang="scss">
  .navbar {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin: 0 20px;
    padding: 20px;
  }

  .logo {
    width: 15%;
  }

  .logo-img {
    width: 100%;
  }

  .right-side {
    display: flex;
    align-items: center;
  }

  .icons {
    display: flex;
    .icon-link {
      margin-right: 15px;
      cursor: pointer;
    }
  }
  .icon-button {
    display: flex;
    width: 30px;
    height: 30px;
    justify-content: center;
    align-items: center;
    /* padding: 6px; */
    border-radius: 100px;
    background-color: #f096a7;
    color: white;
  }

  .opensea-icon {
    width: 16px;
    height: 16px;
  }

  .connect-button {
    font-family: Comfortaa;
    background-color: #f6bcca;
    padding: 12px;
    border-radius: 30px;
    margin-left: 30px;
    cursor: pointer;
  }

  .menu-button {
    display: none;
  }

  @media screen and (max-width: 768px) {
    .navbar {
      display: flex;
      justify-content: space-between;
      align-items: center;
      margin: 0 0px;
      padding: 20px;
    }
    .right-side {
      display: none;
    }

    .logo {
      width: 40%;
    }

    .menu-button {
      width: 10%;
      display: block;
    }
  }
</style>
