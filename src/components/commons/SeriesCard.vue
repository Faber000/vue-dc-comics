<template>
  <div class="container">
     <div class="serie">
        <img :src="image" :alt="title">
        <h3>{{title}}</h3>
     </div>
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
    }
}
</script>

<style lang="scss" scoped>

.serie {

    img {
        width: 100%;
        height: 100%;
    }
    
    h3 {
        font-size: 15px;
        color: white;
    }

}
</style>