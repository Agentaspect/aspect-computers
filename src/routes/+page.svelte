<script>
	import Box from "$lib/Box.svelte";
	import HeadingBox from "$lib/HeadingBox.svelte";
	import Hero from "$lib/hero.svelte";

</script>
<Hero/>

<section>
    <div class="outer bg-gradient-gray">
        <div class="inner auto-fit">
            <HeadingBox heading="Check out our products and pages!"/>
            <Box heading="About us"/>
            <Box heading="Business"/>
            <Box heading="Products"/>
            <Box heading="placeholder"/>
            <Box heading="placeholder"/>
        </div>  
    </div>
</section>


<style>
    .inner {
        padding-block: 8rem;
    }
</style>