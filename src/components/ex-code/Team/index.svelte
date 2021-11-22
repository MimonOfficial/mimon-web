<script lang="ts">
  import TeanCard from './TeamCard.svelte'

  interface Team {
    image: string
    name: string
    explain: string
    twitter: string
  }

  const teamData: Array<Team> = [
    {
      image: '/assets/team1.png',
      name: 'Patxi',
      explain: 'Untill the day Bitcoin becomes the world number one surrency.',
      twitter: 'https://twitter.com/MIMON_OFFICIAL',
    },
    {
      image: '/assets/team1.png',
      name: 'Linling',
      explain:
        'If a pill that keeps young forever, this guy will sell everything that has even all of bitcoin just to acquire some.',
      twitter: 'https://twitter.com/MIMON_OFFICIAL',
    },
    {
      image: '/assets/team1.png',
      name: 'Elixir',
      explain: 'Likes cats, developed a blockchain called popcateum.',
      twitter: 'https://twitter.com/elixirevo',
    },
    {
      image: '/assets/team1.png',
      name: 'Scale',
      explain:
        'This person thinks own brain is being controlled by the brain in the vat. Absolute mental this guy.',
      twitter: 'https://twitter.com/scaeil',
    },
    {
      image: '/assets/team1.png',
      name: 'Means',
      explain: 'Wants to float in the Mediterranean sea and loves seafood.',
      twitter: 'https://twitter.com/m_ean_s',
    },
    {
      image: '/assets/team1.png',
      name: 'Songul',
      explain:
        'Going to run a guest house on an island. All Mimon holders are entitled for free access!',
      twitter: 'https://twitter.com/songgul_',
    },
  ]
</script>

<div class="wrap">
  <div class="content-wrap">
    <div class="paragraph-title">
      <b>THE TEAM</b>
    </div>
    <div class="team-section">
      {#each teamData as item}
        <TeanCard
          image={item.image}
          name={item.name}
          explain={item.explain}
          twitter={item.twitter}
        />
      {/each}
    </div>
  </div>
</div>

<style>
  .content-wrap {
    display: flex;
    justify-content: space-between;
    margin: 0 20px;
    padding-top: 100px;
    padding-bottom: 100px;
    flex-direction: column;
  }

  .paragraph-title {
    font-size: 2.5rem;
    margin-bottom: 50px;
  }

  .team-section {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
  }

  @media screen and (max-width: 768px) {
    .content-wrap {
      display: flex;
      justify-content: space-between;
      margin: 0 20px;
      padding-top: 50px;
      padding-bottom: 50px;
      flex-direction: column;
    }

    .paragraph-title {
      font-size: 2.5rem;
      margin-bottom: 50px;
    }

    .team-section {
      display: flex;
      flex-wrap: wrap;
      justify-content: space-between;
    }
  }
</style>
