<template>
    <section>
        <div class="container">
            <div class="services">
                <div class="service">
                    <img class="item" src="../assets/img/buy-comics-digital-comics.png" alt="">
                    <h2>DIGITAL COMICS</h2>
                </div>
                <div class="service">
                    <img class="item" src="../assets/img/buy-comics-merchandise.png" alt="">
                    <h2>DC MERCHANDISE</h2>
                </div>
                <div class="service">
                    <img class="item" src="../assets/img/buy-comics-subscriptions.png" alt="">
                    <h2>SUBSCRIPTIONS</h2>
                </div>
                <div class="service">
                    <img class="item" src="../assets/img/buy-comics-shop-locator.png" alt="">
                    <h2>COMIC SHOP LOCATOR</h2>
                </div>
                <div class="service">
                    <img class="item" src="../assets/img/buy-dc-power-visa.svg" alt="">
                    <h2>DC POWER VISA</h2>
                </div>
            </div>
        </div>
    </section>
</template>

<style lang="scss" scoped>

section {
    background-color: rgb(2, 130, 249);
    height: 120px;
}

.container {
    margin: auto;
    width: 70%;
    height: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
}

.services, .service {
    display: flex;
    justify-content: center;
    align-items: center;
}

.service {
    margin-left: 50px;
    width: 150px;
}

h2 {
    color: white;
    font-size: 15px;
}

.item {
    height: 50px;
    margin-right: 10px;
}

</style>