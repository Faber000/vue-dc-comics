<template>
    <section>
        <div class="hero-container"></div>
        <SeriesSection/>
    </section>
</template>

<script>
import SeriesSection from './sections/SeriesSection.vue';

export default {
    name: 'BaseMainTop',
    components: {
      SeriesSection,
    }
}
</script>


<style lang="scss" scoped>

h1 {
    color: white;
}

.hero-container {
    width: 100%;
    height: 300px;
    background-image: url('../assets/img/jumbotron.jpg');
    background-size: cover;
}
</style>