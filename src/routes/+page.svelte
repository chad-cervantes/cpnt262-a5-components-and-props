<script>
  //imported card info
  import Card from '../lib/components/Card.svelte';
  
  //Card object array
  const cardObj = [
    {name: 'Jose',
    age:'25 years old',
    location: 'Los Angeles',
    position: 'striker',
    team: 'LA Galaxy'},

    {name: 'Daniel',
    age:'23 years old',
    location: 'New York City',
    position: 'defender',
    team: 'NYCFC'},

    {name: 'Reggie',
    age:'21 years old',
    location: 'Seattle',
    position: 'midfielder',
    team: 'Seattle Sounders'}
  ];
 
</script>

<!--For each loop-->
{#each cardObj as card}
  <Card {...card} />
{/each}


