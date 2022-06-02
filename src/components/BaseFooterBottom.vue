<template>
    <section>
        <div class="container">
            <button>SIGN-UP NOW!</button>
            <div class="social">
                <h2>Follow Us</h2>
                <img class="item" src="../assets/img/footer-facebook.png" alt="">
                <img class="item" src="../assets/img/footer-twitter.png" alt="">
                <img class="item" src="../assets/img/footer-youtube.png" alt="">
                <img class="item" src="../assets/img/footer-pinterest.png" alt="">
                <img class="item" src="../assets/img/footer-periscope.png" alt="">
            </div>
        </div>
    </section>
</template>

<style lang="scss" scoped>

section {
    background-color: rgb(48, 48, 48);
    height: 100px;
}

.container {
    margin: auto;
    width: 70%;
    height: 100%;
    display: flex;
    align-items: center;
    justify-content: space-between;
}

button {
    background-color: rgb(48, 48, 48);
    border: 3px solid rgb(2, 130, 249);
    color: white;
    height: 50px;
    width: 100px;
}

.social {
    display: flex;
    align-items: center;
}

.social * {
    margin-left: 15px;
}

h2 {
    color: rgb(2, 130, 249);
}

</style>