<script>
  //Primary Navbar
   const navItems = [
    {name: 'Home', href: '/'},
    {name: 'About', href: '/about'},
    {name: 'Story', href: '/story'},
    {name: 'Contact', href: '/contact'}
  ];

</script>

<!--Primary Nav Links decoration-->
<header class="bg-black text-white text-xl flex justify-between p-4">
  <div>logo</div>
  <nav>
    <ul class="flex justify-around gap-4">
      {#each navItems as {name, href}}
        <li><a {href}>{name}</a></li>
      {/each}  
    </ul>
  </nav>
</header>