<script>
  import LinkContainer from './lib/LinkContainer.svelte'
  import Header from './lib/Header.svelte';

  let data = [
    {
      category: 'laptops',
      text: 'Power your workday with a range of reconditioned laptops.',
      image: '/laptop-fixed.png',
      toggled: 'true'
    },
    {
      category: 'desktops',
      text: 'Stay on budget with refurbished towers, all-in-ones and more.',
      image: '/desktop-fixed.png',
      toggled: 'true'
    },
    {
      category: 'printers',
      text: 'Cut costs, not corners with like-new printers built to perform.',
      image: '/printer-fixed.png',
      toggled: 'true'
    },
  ]
</script>

<header>
  <Header bind:data={data}/>
</header>

<main>
 
  <LinkContainer bind:data={data} />
</main>

<style>
 
</style>
