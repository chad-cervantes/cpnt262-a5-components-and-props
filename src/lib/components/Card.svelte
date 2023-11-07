<script>
  //Card component variables
  export let title;
  export let age;
  export let location;
  export let position;
  export let description;
  export let team;
  export let img;
  export let url;
</script>

<!--Card article-->
  <article class="lg:w-[550px] bg-red-300 bg-contain  bg-cover text-xl text-center border-solid scale-75 m-auto rounded-[5%] p-8 hover:bg-orange-400 active:bg-teal-500 transition ease-linear duration-150">
    <a href={url}>
      <img src={img} class="w-[500px] h-[350px] m-auto rounded-[5%]" alt="player profile pic">
      <h3 class="p-4 text-6xl">{title}</h3>
      <p class="p-1 text-3xl text-orange-950 font-serif">{age}</p>
      <p class="p-1 text-3xl text-orange-950 font-serif">{location}</p>
      <p class="p-1 text-3xl text-orange-950 font-serif">{position}</p>
      <p class="p-1 text-3xl text-orange-950 font-serif">{description}</p>
      <p class="p-1 text-3xl text-orange-950 font-serif">{team}</p>
    </a>
  </article>
