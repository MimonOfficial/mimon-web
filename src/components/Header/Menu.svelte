<script lang="ts">
  import Fa from 'svelte-fa'
  import { faTimes } from '@fortawesome/free-solid-svg-icons'
  import { links } from '../../links/index'

  export let showModal: boolean
</script>

{#if showModal}
  <div class="modal">
    <div class="icon-wrap">
      <div class="icon" on:click><Fa icon={faTimes} size="2x" /></div>
    </div>
    <div class="struct">
      <div class="menu">
        <div class="menu-button">
          <a href={links.opensea} target="_blank">OpenSea</a>
        </div>
        <div class="menu-button">
          <a href={links.instagram} target="_blank">Instagram</a>
        </div>
        <div class="menu-button">
          <a href={links.medium} target="_blank">Medium</a>
        </div>
        <div class="menu-button">
          <a href={links.twitter} target="_blank">Twitter</a>
        </div>
        <div class="menu-button">
          <a href={links.discord} target="_blank">Discord</a>
        </div>
      </div>
    </div>
  </div>
{/if}

<style>
  .modal {
    width: 100%;
    height: 100%;
    position: fixed;
    top: 0;
    left: 0;
    background: #ffd0d0;
    z-index: 100;
  }

  .icon-wrap {
    display: flex;
    justify-content: flex-end;
  }

  .icon {
    padding: 26px;
    cursor: pointer;
  }
  .struct {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    margin-top: 30%;
  }

  .menu {
    font-size: 1.5rem;
    font-family: Comfortaa;
  }

  .menu-button {
    padding: 15px;
  }
</style>
