<script>
    let{
        heading,
        src,
    }=$props()
</script>
<div class="flow bg-gradient-black">
    <img src="{src}" alt="">
    <h3>{heading}</h3>
    <p>dont forget to remove this or do something else!</p>
    <a href="/">read more &raquo;</a>
</div>

<style>
    div {
        position: relative;
        padding: 2rem;
        border-radius: 1rem;
        font-size: 1.125rem;
    }


    img {
        position: absolute;
        max-width: 3.5rem;
        top: -1.5rem;
    }
    a {
        display: inline-block;
        font-weight: bold;
    }
</style>