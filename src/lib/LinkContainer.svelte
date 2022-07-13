<script>
    import Link from "./Link.svelte";

const data = [
    {
      category: 'laptops',
      text: 'Power your workday with a range of reconditioned laptops.',
      image: '/laptop-fixed.png',
    },
    {
      category: 'desktops',
      text: 'Stay on budget with refurbished towers, all-in-ones and more.',
      image: '/desktop-fixed.png',
    },
    {
      category: 'printers',
      text: 'Cut costs, not corners with like-new printers built to perform.',
      image: '/printer-fixed.png',
    },
  ]
</script>

<section>
    {#each data as link}
    <Link {...link} />
    {/each}
</section>