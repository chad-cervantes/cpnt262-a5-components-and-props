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
<article>
  <div></div>
  <h3>{name}</h3>
  <img src={img} alt="">
  <p>{age}</p>
  <p>{location}</p>
  <p>{position}</p>
  <p>{team}</p>
</article>
