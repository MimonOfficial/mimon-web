<script>
  import Fa from 'svelte-fa'
  import { faChevronDown } from '@fortawesome/free-solid-svg-icons'

  let btnState = true
  $: faqData

  let faqData = [
    {
      number: '1',
      title: 'When can I purchase Mimon?',
      content:
        'You can participate in the free airdrop event through Discord. The pre-mint and public mint are scheduled for mid-December. A detailed schedule will be announced through the community. Pit-a-pat!!',
      state: false,
    },
    {
      number: '2',
      title: 'What blockchain network does Mimon use?',
      content:
        'The first 10,000 Mimons will be issued using ERC-721. Additional editions will use Polygon to reduce gas costs.',
      state: false,
    },
    {
      number: '3',
      title: 'How can I mint Mimon?',
      content: 'First, make sure you are associated with the metamask wallet. (medium link)',
      state: false,
    },
    {
      number: '4',
      title: 'Where can I see my Mimon after purchase?',
      content:
        'Your Mimon NFT will be displayed on the address you used to purchase Mimon or in your metamask wallet. Once you’ve completed minting, you may also check your purchase through My Collections in OpenSeas.',
      state: false,
    },
    {
      number: '5',
      title: 'Is the Mimon Project reliable?',
      content:
        'We are well aware of the declining value of existing projects due to the few projects abandoning their initial work for mass production projects. The Mimon Project’s consistent on/offline activities will demonstrate our promising value creation.',
      state: false,
    },
    {
      number: '6',
      title: 'What can I do with Mimon?',
      content:
        'Each Mimon is your own dream and desire. Personalize your Mimon experience to realize your fantasies with a proprietary license.',
      state: false,
    },
  ]

  function popupBtn(stateNum) {
    faqData[stateNum].state = !faqData[stateNum].state
  }

  function test() {
    console.log(faqData[0])
    console.log(faqData[0].state)
  }
</script>

<div class="background">
  <div class="wrap">
    <div class="struct">
      <div class="title-side">
        <div class="title" on:click={test}>FAQ</div>
      </div>
      <div class="box-side">
        {#each faqData as item, index}
          <div class="box-wrap">
            <div class="box">
              <div class="box-title-section">
                <div class="box-number">{item.number}.</div>
                <div class="box-title">{item.title}</div>
              </div>
              <div
                class="box-button"
                on:click={() => {
                  popupBtn(index)
                }}
              >
                <Fa icon={faChevronDown} size="1x" />
              </div>
            </div>
            {#if item.state === true}
              <div class="content-box">
                <div class="box-content">
                  {item.content}
                </div>
              </div>
            {/if}
          </div>
        {/each}
      </div>
    </div>
  </div>
</div>

<style>
  .background {
    background: #fff9fa;
    border-bottom-style: solid;
    border-bottom-color: #211919;
    border-bottom-width: 5px;
  }
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

  .box-wrap {
    width: 100%;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    align-items: center;
    margin-top: 20px;
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
    /* margin-bottom: 15px; */
  }

  .content-box {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 15px 60px 15px 60px;
    width: 100%;
    border-left: 3px solid #211919;
    border-right: 3px solid #211919;
    border-bottom: 3px solid #211919;
    box-sizing: border-box;
    /* margin-bottom: 15px; */
    background-color: #fbdee5;
  }

  .box-content {
    font-family: Comfortaa;
    font-size: 1rem;
    color: #211919;
    line-height: 30px;
  }

  .box-title-section {
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
    cursor: pointer;
  }

  .box-button:active {
    /* width: 35px;
    height: 35px; */
    background-color: #f096a7;
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
  @media screen and (max-width: 768px) {
    .box {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 15px 21px 15px 31px;
      width: 100%;
      border: 3px solid #211919;
      box-sizing: border-box;
      line-height: 35px;
    }

    .box-number {
      margin-right: 15px;
      display: flex;
      align-items: center;
    }

    .content-box {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 15px 30px 15px 30px;
      width: 100%;
      border-left: 3px solid #211919;
      border-right: 3px solid #211919;
      border-bottom: 3px solid #211919;
      box-sizing: border-box;
      /* margin-bottom: 15px; */
      background-color: #fbdee5;
    }
  }
</style>
