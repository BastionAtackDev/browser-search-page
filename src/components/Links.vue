<script setup>
    import link1 from './link1.vue'
    import link2 from './link2.vue'
    import link3 from './link3.vue'
    import link4 from './link4.vue'
    import link5 from './link5.vue'
</script>
<template>
    <section>
        <div id="grid">
            <link1 />
            <link2 />
            <link3 />
            <link4 />
            <link5 />
        </div>
    </section>
</template>
<style>
    #grid{
        display: grid;
        grid-template-columns:  repeat(auto-fit, minmax(10svw,15svw));
        grid-template-rows: 20svw;
    }
    section{
        margin-left: 6.5svw;
    }
</style>