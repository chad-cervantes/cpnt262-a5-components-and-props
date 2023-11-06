<script>
  //imported card info
  import Card from '../lib/components/Card.svelte';
  
  //Card object array
  const cardObj = [
    {img: '/images/profile-pic.jpg',
    name: 'Jose',  
    age:'25 years old',
    location: 'Los Angeles',
    description: 'height of 6ft',
    position: 'striker',
    team: 'LA Galaxy'},

    { img: '/images/profile-pic.jpg',
    name: 'Daniel',
    age:'23 years old',
    location: 'New York City',
    description: 'height of 5.8ft',
    position: 'defender',
    team: 'NYCFC'},

    {img: '/images/profile-pic.jpg',
    name: 'Reggie',
    age:'21 years old',
    location: 'Seattle',
    description: 'height of 5.6ft',
    position: 'midfielder',
    team: 'Seattle Sounders'}
 ];
    
</script>

<!--For each loop-->
{#each cardObj as card}
  <Card {...card} />
{/each}




