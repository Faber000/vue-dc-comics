<template>
    <header class="header">
        <div class="header__container">
            <nav class="header__nav">
                <div class="logo-div">
                    <img class="logo" src="../assets/img/dc-logo.png"/>
                </div>
                <ul>
                    <li>CHARACTERS</li>
                    <li>COMICS</li>
                    <li>MOVIES</li>
                    <li>TV</li>
                    <li>GAMES</li>
                    <li>COLLECTIBLES</li>
                    <li>VIDEOS</li>
                    <li>FANS</li>
                    <li>NEWS</li>
                    <li>SHOP</li>
                </ul>
            </nav>
        </div>      
    </header>
</template>

<script></script>

<style lang="scss" scoped>

.header {  

    &__container {
        height: 80px;
        margin: auto;
        width: 70%;
        display: flex;
        align-items: center;
    }

    &__nav { 
            width: 100%;
            display: flex;
            align-items: center;
            justify-content: space-between;

        ul {
            display: flex;
            list-style-type: none;

            li {
                margin-right: 20px;
                font-size: 17px;
                color: black;
            }
        }
    }
}

.logo {
    height: 60px;
}

.logo-div {
    display: flex;
    align-items: flex-end;
}

</style>