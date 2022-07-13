<script>
    import LinkToggle from "./LinkToggle.svelte";

    export let data
</script>

<h1>Staples Fix: Svelte</h1>
<div>
    {#each data as link}
    <LinkToggle bind:name={link.category}/>
    {/each}
</div>
<style>
    h1{
        text-align: center;
        background: #CE0000;
        color: #fff;
        padding: 7px;
        margin-bottom: 12px;
    }
    div{
        text-align: center;
        margin: 0 auto;
    }
    
</style>