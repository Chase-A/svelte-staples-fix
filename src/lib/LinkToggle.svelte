<script>
    export let name

    function handleClick(e){
        console.log('test')
        
    }
</script>

<button on:click={handleClick}>{name}</button>

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