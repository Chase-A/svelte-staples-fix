<script>
  import Link from "./Link.svelte";

  export let data
</script>

<section>
  {#each data as link}
    <Link {...link} />
  {/each}
</section>

<style>
  section {
    margin: 10px;
  }
</style>
