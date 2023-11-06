<script>
  //Card component variables
  export let name;
  export let age;
  export let location;
  export let position;
  export let team;
  export let img;
</script>

<!--Card article-->
<article class="lg:bg-pink-400 text-xl p-8 m-auto text-center  lg:border-x-[600px] lg:border-y-[50px] border-solid">
  <img src={img} class="w-[250px] h-[250px] m-auto" alt="player profile pic">
  <h3 class="p-4 text-3xl">{name}</h3>
  <p class="p-1 text-green-200">{age}</p>
  <p class="p-1 text-green-200">{location}</p>
  <p class="p-1 text-green-200">{position}</p>
  <p class="p-1 text-green-200">{team}</p>
</article>
