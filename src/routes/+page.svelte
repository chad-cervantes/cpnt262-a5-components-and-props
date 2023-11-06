<script>
  //imported card info
  import Card from '../lib/components/Card.svelte';
  
  //Card object array
  const cardObj = {
    name: 'Jose',
    age:'25 years old',
    location: 'Los Angeles',
    position: 'striker',
    team: 'LA Galaxy'
  };
 
</script>

<!--Rendered card components-->
<Card {...cardObj} />

