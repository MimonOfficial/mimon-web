<script>
  import Fa from 'svelte-fa'
  import { faChevronDown } from '@fortawesome/free-solid-svg-icons'
</script>

<div class="wrap">
  <div class="struct">
    <div class="title-side">
      <div class="title">FAQ</div>
    </div>
    <div class="box-side">
      <div class="box">
        <div class="box-title-section">
          <div class="box-number">1.</div>
          <div class="box-title">When can I purchase Mimon?</div>
        </div>
        <div class="box-button">
          <Fa icon={faChevronDown} size="1x" />
        </div>
      </div>
    </div>
  </div>
</div>

<style>
  .struct {
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    align-items: center;
    margin: 0 40px;
    padding-top: 85px;
    padding-bottom: 95px;
    border-top-color: #211919;
    border-top-width: 5px;
    background: #fff9fa;
  }
  .box-side {
    width: 100%;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    align-items: center;
  }

  .box-title-section {
    display: flex;
    flex-direction: row;
    font-family: Comfortaa;
    font-size: 1.5rem;
    color: #211919;
    font-weight: bold;
  }

  .box {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 15px 21px 15px 31px;
    width: 100%;
    border: 3px solid #211919;
    box-sizing: border-box;
    margin-bottom: 15px;
  }

  box-title-section {
    font-family: Comfortaa;
    font-size: 1.5rem;
    color: #211919;
    font-weight: bold;
  }

  .box-number {
    margin-right: 15px;
  }

  .box-button {
    padding: 4px;
  }

  .box-button:hover {
    /* width: 35px;
    height: 35px; */
    background-color: #F096A7;
    padding: 4px;
    color: #fff9fa;
  }
  .title {
    font-family: Comfortaa;
    font-size: 3.125rem;
    color: #211919;
    font-weight: bold;
    margin-bottom: 42px;
  }
</style>
