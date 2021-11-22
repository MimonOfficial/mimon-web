<script lang="ts">
</script>

<div class="background">
  <div class="wrap">
    <div class="content-wrap">
      <div class="paragraph-title">
        <b
          >MIMON<br />
          GALLERY</b
        >
      </div>
      <div class="img-slide">
        <div class="img-wrap">
          <img class="mimon-img" src="/assets/mimon1.png" alt="mimon1" />
          <img class="mimon-img" src="/assets/mimon2.png" alt="mimon2" />
          <img class="mimon-img" src="/assets/mimon3.png" alt="mimon3" />
        </div>
      </div>
    </div>
  </div>
</div>

<style>
  .background {
    background-image: url('/assets/gallery_background.png');
    background-size: 100% 100%;
    background-repeat: no-repeat;
  }

  .content-wrap {
    display: flex;
    justify-content: space-between;
    /* align-items: center; */
    margin: 0 20px;
    padding-top: 100px;
    padding-bottom: 100px;
    flex-direction: column;
  }

  .paragraph-title {
    font-size: 2.5rem;
    margin-bottom: 20px;
  }

  .img-wrap {
    display: flex;
    justify-content: space-between;
  }

  .mimon-img {
    width: 33%;
    padding: 10px;
    box-sizing: border-box;
  }

  @media screen and (max-width: 768px) {

  }
</style>
