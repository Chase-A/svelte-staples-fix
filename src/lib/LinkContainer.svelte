<script>
  import Link from "./Link.svelte";

  export let data
</script>

<section>
  {#each data as link}
    {#if link.toggled}
    <Link {...link} />
    {/if}
  {/each}
</section>

<style>
  section {
    margin: 0 auto;
    max-width: 600px;
  }

  @media (min-width: 800px){
    section{
      display: flex;
      max-width: 1050px;
    }
  }
</style>
