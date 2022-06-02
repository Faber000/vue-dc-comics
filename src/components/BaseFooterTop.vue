<template>
    <section>
        <img class="logo_bg" src="../assets/img/dc-logo-bg.png" alt="">
        <div class="container">
            <div class="lists">
                <div class="col">
                    <ul>
                        <li class="big">DC COMICS</li>
                        <li>CIAO</li>
                        <li>CIAO</li>
                        <li>CIAO</li>
                        <li>CIAO</li>
                        <li>CIAO</li>
                        <li>CIAO</li>
                        <li>CIAO</li>
                    </ul>
                    <ul>
                        <li class="big">SHOP</li>
                        <li>CIAO</li>
                        <li>CIAO</li>
                    </ul>
                </div>

                <div class="col">
                    <ul>
                        <li class="big">DC</li>
                        <li>CIAO</li>
                        <li>CIAO</li>
                        <li>CIAO</li>
                        <li>CIAO</li>
                        <li>CIAO</li>
                        <li>CIAO</li>
                        <li>CIAO</li>
                        <li>CIAO</li>
                        <li>CIAO</li>
                        <li>CIAO</li>
                        <li>CIAO</li>
                    </ul>
                </div>
                <div class="col">
                    <ul>
                        <li class="big">SITES</li>
                        <li>CIAO</li>
                        <li>CIAO</li>
                        <li>CIAO</li>
                        <li>CIAO</li>
                        <li>CIAO</li>
                    </ul>
                </div>
            </div>
        </div>
    </section>
</template>

<style lang="scss" scoped>

section {
    height: 400px;
    background-image: url('../assets/img/footer-bg.jpg');
    position: relative;
    overflow-y: hidden;
    color: gray;
}

.logo_bg {
    position: absolute;
    top: -80px;
    right: 200px;
}

.lists {
    display: flex;
}

.container {
    margin: auto;
    width: 70%;
    height: 100%;
    display: flex;
    align-items: center;
}

.big {
    color: white;
    font-size: 20px;
}

li {
    list-style-type: none;
}

.col {
    margin: 30px;
}

</style>