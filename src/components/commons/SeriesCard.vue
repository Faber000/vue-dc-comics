<template>
    <div class="serie">
        <img :src="image" :alt="title">
        <h3>{{title}}</h3>
    </div>
</template>

<script>
export default {
    name: 'SeriesCard',
    props: {
        title: String,
        image: {
            type: String,
        },
    },
}
</script>

<style lang="scss" scoped>

.serie {

    img {
        width: 160px;
        height: 160px;
    }

    h3 {
        font-size: 15px;
        color: white;
    }

}
</style>