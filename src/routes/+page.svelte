<script>
  import Header from '../lib/components/Header.svelte'; 
  //imported card info
  import Card from '../lib/components/Card.svelte';
  
  //Card object array
  const cardObj = [
    {img: '/images/profile-pic.jpg',
    name: 'Jose',  
    age:'25 years old',
    location: 'Los Angeles',
    position: 'striker',
    team: 'LA Galaxy'},

    { img: '/images/profile-pic.jpg',
    name: 'Daniel',
    age:'23 years old',
    location: 'New York City',
    position: 'defender',
    team: 'NYCFC'},

    {img: '/images/profile-pic.jpg',
    name: 'Reggie',
    age:'21 years old',
    location: 'Seattle',
    position: 'midfielder',
    team: 'Seattle Sounders'}
 ];
    
</script>

<Header />

<!--For each loop-->
{#each cardObj as card}
  <Card {...card} />
{/each}




