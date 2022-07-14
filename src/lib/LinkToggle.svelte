<script>
    export let link

    function handleClick(){
        link.toggled = !link.toggled
    }
</script>

<button on:click={handleClick}>{link.category}</button>

<style>
    button{
        text-transform: uppercase;
        background: none;
        border: #CE0000 2px solid;
        color: #CE0000;
        font-weight: 700;
        padding: 5px 10px;
        margin: 5px;
    }
</style>