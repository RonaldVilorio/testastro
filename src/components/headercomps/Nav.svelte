<script>
  const navItems = ['Projects', 'About'];
</script>

<nav class="mx-auto mt-6 p-2 max-w-fit bg-green-400 ribbon">
  <ul class="flex">
    {#each navItems as item}
      <li class="mx-5">{item}</li>
    {/each}
  </ul>
</nav>

<style>
  .ribbon {
    clip-path: polygon(0 0, 100% 0, 100% 100%, 50% 70%, 0 100%);
  }
</style>
