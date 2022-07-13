<script>
    export let category
    export let text
    export let image
</script>

<section>
    <div>
        <h2>refurbished<br/>{category}</h2>
        <p>{text}</p>
        <h3>shop now</h3>
    </div>

    <img
        src={image}
        alt="a laptop computer"
    />
</section>

<style>
    *{
        margin: 0;
        padding: 0;
    }

    section {
        display: flex;
        box-shadow: 0px 1px 9px -1px rgba(0, 0, 0, 0.25);
        place-items: center;
        overflow: hidden;
        margin-top: 16px;
    }
    div {
        padding: 20px;
        flex-basis: 60%;
    }
    h2{
        font-size: 16px;
        font-weight: 300;
        margin-bottom: 12px;
    }
    p{
        font-size: 10px;
        margin-bottom: 24px;
        width: 50vw;
    }
    h3{
        font-size: 12px;
        font-weight: 700;
        color: #0099CC
    }
    h2, h3{
        text-transform: uppercase;
    }
    img{
        max-height: 150px;
        max-width: 200px;
        padding: 20px;
    }
</style>
