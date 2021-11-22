<script>
</script>

<div class="background">
  <div class="wrap">
    <div class="struct">
      <div class="left-side">
        <div class="logo">
          <img class="logo-img" src="/assets/logo.png" alt="logo" />
        </div>
        <div class="logo-bottom-text">
          10,000 unique dream, fulfill your desire, Mimon!
        </div>
      </div>
      <div class="right-side">
        <div class="link-list">
          <div class="link-button">Opensea</div>
          <div class="link-button">Opensea</div>
          <div class="link-button">Opensea</div>
          <div class="link-button">Opensea</div>
          <div class="link-button">Opensea</div>
        </div>
        <div class="email">E-Mail. mimon@mimons.io</div>
        <div class="copyright">
          Copyright 2021 DE3SFUL LABS, All rights reserved.
        </div>
        <div class="copyright-mobile">
          Copyright 2021 DE3SFUL LABS,
        </div>
        <div class="copyright-mobile">
          All rights reserved.
        </div>
      </div>
    </div>
  </div>
</div>

<style>
  .background {
    background-color: #fbdee5;
  }

  .struct {
    display: flex;
    justify-content: space-between;
    /* align-items: center; */
    margin: 0 40px;
    padding: 67px 0px;
  }

  .left-side {
    width: 45%;
  }

  .right-side {
    width: 55%;
  }

  .logo {
    width: 25%;
    margin-bottom: 38px;
  }

  .logo-img {
    width: 100%;
  }

  .logo-bottom-text {
    font-family: Sansation Light;
    font-size: 1.125rem;
    color: #484848;
    font-weight: 300;
  }

  .link-list {
    display: flex;
    justify-content: flex-end;
    align-items: center;
    margin-bottom: 57px;
  }

  .link-button {
    font-family: Sansation Light;
    font-size: 1.125rem;
    color: #484848;
    font-weight: 300;
    margin-left: 38px;
  }

  .email {
    display: flex;
    justify-content: flex-end;
    font-family: Sansation Light;
    font-size: (1.125rem);
    color: #484848;
    font-weight: 300;
    margin-bottom: 20px;
  }

  .copyright {
    display: flex;
    justify-content: flex-end;
    font-family: Sansation Light;
    font-size: (1.125rem);
    color: #484848;
    font-weight: 300;
    margin-bottom: 41px;
  }

  .copyright-mobile {
    display: none;
  }

  @media screen and (max-width: 768px) {
    .logo {
      width: 60%;
      margin-bottom: 38px;
    }
    .struct {
      display: flex;
      flex-direction: column;
      justify-content: space-between;
      /* align-items: center; */
      margin: 0 40px;
      padding: 67px 0px;
    }
    .left-side {
      width: 100%;
      margin-bottom: 30px;
    }

    .right-side {
      width: 100%;
    }

    .link-list {
      display: flex;
      flex-direction: column;
      align-items: flex-end;
      margin-bottom: 10px;
    }

    .link-button {
      display: flex;
      font-family: Sansation Light;
      font-size: 1.125rem;
      color: #484848;
      font-weight: 300;
      margin-bottom: 10px;
    }

    .copyright {
      display: none;
    }
    .copyright-mobile {
      display: flex;
      justify-content: flex-end;
      font-family: Sansation Light;
      font-size: (1.125rem);
      color: #484848;
      font-weight: 300;
      margin-bottom: 10px;
    }

    .link-list-mobile {
      display: flex;
      flex-direction: column;
      align-items: flex-end;
    }
  }
</style>
