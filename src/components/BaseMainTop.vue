<template>
    <section>
        <div class="hero-container">

        </div>
        <div class="container">
            <h1>Content goes here</h1>
        </div>
    </section>
</template>

<style lang="scss" scoped>

.container {
    background-color: black;
    height: 100px;
    display: flex;
    justify-content: center;
    align-items: center;
}

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