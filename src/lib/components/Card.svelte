<script>
  //Card component variables
  export let name;
  export let age;
  export let location;
  export let position;
  export let description;
  export let team;
  export let img;
  export let url;
</script>

<!--Card article-->

  <article class="w-[550px] lg:bg-red-50 bg-contain  bg-cover text-xl text-center border-solid scale-75 m-auto rounded-[10%] p-8 hover:bg-orange-200">
   <div>
    <a href={url}>
      <img src={img} class="w-[250px] h-[250px] m-auto rounded-[5%]" alt="player profile pic">
      <h3 class="p-4 text-3xl">{name}</h3>
      <p class="p-1 text-orange-950">{age}</p>
      <p class="p-1 text-orange-950">{location}</p>
      <p class="p-1 text-orange-950">{position}</p>
      <p class="p-1 text-orange-950">{description}</p>
      <p class="p-1 text-orange-950">{team}</p>
    </a>
  </div> 
  </article>
