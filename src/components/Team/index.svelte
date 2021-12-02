<script lang="ts">
  import TeamBox from './TeamBox.svelte'

  interface Team {
    image: string
    name: string
    explain: string
    twitter: string
    position: string
  }

  const teamData: Array<Team> = [
    {
      image: '/assets/team1.jpg',
      name: 'PATXI',
      explain: 'Until the day Bitcoin becomes the worlds number one currency!',
      twitter: 'https://twitter.com/patxikim',
      position: 'Direcitor',
    },
    {
      image: '/assets/team3.png',
      name: 'LINLING',
      explain:
        'If a pill that keeps young forever, she will sell all of bitcoin that she has just to acquire some.',
      twitter: 'https://twitter.com/linlinglife',
      position: 'Artist',
    },
    {
      image: '/assets/team4.jpg',
      name: 'MEANS',
      explain: 'Wants to float in the Mediterranean sea and loves seafood.',
      twitter: 'https://twitter.com/m_ean_s',
      position: 'Artist',
    },
    {
      image: '/assets/team5.jpg',
      name: 'ELIXIR',
      explain: 'This guy Likes cats, developed a blockchain called POPCATEUM.',
      twitter: 'https://twitter.com/elixirevo',
      position: 'Developer',
    },
    {
      image: '/assets/team6.jpg',
      name: 'SONGUL',
      explain:
        'Going to run a guest house on an island. All Mimon holders are entitled for free access!',
      twitter: 'https://twitter.com/songgul_',
      position: 'Planning Manager',
    },
    {
      image: '/assets/team2.png',
      name: 'SCALE',
      explain:
        'This person thinks own brain is being controlled by the brain in the vat. Absolute mental this guy.',
      twitter: 'https://twitter.com/scaeil',
      position: 'Product Manager',
    },
  ]
</script>

<div class="background">
  <div class="wrap">
    <div class="struct">
      <div class="title-side">
        <div class="title">TEAM</div>
      </div>
    </div>
  </div>
  <div class="wrap">
    <div class="struct-content">
      <div class="box-side">
        {#each teamData as item}
          <TeamBox
            image={item.image}
            name={item.name}
            explain={item.explain}
            twitter={item.twitter}
            position={item.position}
          />
        {/each}
      </div>
    </div>
  </div>
  <div>
    <img class="line" src="/assets/component_line_2.png" alt="line" />
    <img class="line-mobile" src="/assets/component_line_mobile.png" alt="line" />
  </div>
</div>

<style lang="scss">
  .background {
    background: #fbdee5;
  }
  .struct {
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    align-items: center;
    margin: 0 40px;
    padding-top: 121px;
    padding-bottom: 34px;
  }

  .struct-content {
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    margin: 0 40px;
    align-items: center;
    padding-bottom: 170px;
  }

  .title-side {
    width: 100%;
    display: flex;
    justify-content: start;
    margin-bottom: 34px;
  }

  .title {
    font-family: Comfortaa;
    font-size: 3.125rem;
    color: #211919;
    font-weight: bold;
  }

  .box-side {
    width: 100%;
    display: flex;
    justify-content: space-between;
    align-items: center;
    flex-wrap: wrap;
  }

  .line {
    display: block;
    width: 100%;
  }

  .line-mobile {
    display: none;
  }

  @media screen and (max-width: 768px) {
    .box-side {
      width: 100%;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
    }

    .line {
      display: none;
      width: 100%;
    }

    .line-mobile {
      display: block;
      width: 100%;
    }
  }
</style>
