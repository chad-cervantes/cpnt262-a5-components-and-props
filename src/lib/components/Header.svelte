<script>
   const navItems = [
    {name: 'Home', href: '/'},
    {name: 'About', href: '/about'},
    {name: 'Story', href: '/story'},
    {name: 'Contact', href: '/contact'}
  ];

</script>


<header>
  <div>logo</div>
  <nav>
    <ul class>
      {#each navItems as {name, href}}
        <li><a {href}>{name}</a></li>
      {/each}  
    </ul>
  </nav>
</header>