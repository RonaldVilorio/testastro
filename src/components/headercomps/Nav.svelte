<script>
  const navItems = ['Projects', 'About'];
</script>

<nav class="mx-auto mt-6 p-2 max-w-fit bg-white">
  <ul class="flex">
    {#each navItems as item}
      <li class="mx-5">{item}</li>
    {/each}
  </ul>
</nav>

<style>
</style>
