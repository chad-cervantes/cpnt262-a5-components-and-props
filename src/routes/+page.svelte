<h1>List of current MLS soccer players</h1>

<script>
  //imported card info
  import Card from '../lib/components/Card.svelte';

  //imported object array from data.js
  import {cardObj} from '../lib/data.js'; 
</script>

<!--For each loop-->
{#each cardObj as card}
  <Card {...card} />
{/each}






