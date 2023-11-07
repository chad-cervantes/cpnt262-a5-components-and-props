<h1 class="p-6 text-center lg:text-7xl bg-rose-400 font-mono"> Canada Soccer League</h1>

<div>
  <img src='/images/pexels-johannes-plenio-1103969.jpg' alt="soccer stadium" class="w-[1590px]">
</div>

<h1 class="p-6 text-center lg:text-7xl bg-rose-400 font-mono">List of current CSL soccer players</h1>

<script>
  //imported card info
  import Card from '../lib/components/Card.svelte';

  //imported object array from data.js
  import {cardObj} from '../lib/data.js'; 
</script>

<!--For each loop-->
<section class="grid grid-cols-2">
  {#each cardObj as card}
    <Card {...card} />
  {/each}
</section>





