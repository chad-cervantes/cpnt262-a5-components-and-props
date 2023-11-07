<script>
  //Footer Nav
  const navItems = [
   {name: 'Home', href: '/'},
   {name: 'About', href: '/about'},
   {name: 'Story', href: '/story'},
   {name: 'Contact', href: '/contact'}
 ];

</script>

<!--Footer Nav links-->
<header class="bg-blue-400 text-white text-l flex justify-around p-4">
 <nav>
   <ul class="flex justify-around gap-4">
     {#each navItems as {name, href}}
       <li><a {href}>{name}</a></li>
     {/each}  
   </ul>
 </nav>
</header>

<!--Copyright-->
<p class="text-center bg-blue-400 text-white text-l p-4">&copy 2023 Canada Soccer League | All Rights Reserved</p>