<template>
    <header>
        <div class="container">
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
    &__nav { 
            display: flex;
            justify-content: space-between;

        ul {
            display: flex;
            align-items: center;
            list-style-type: none;

            li {
                margin-right: 10px;
                font-size: 13px;
            }
        }
    }
}

.container {
    margin: auto;
    width: 70%;
    height: 100%;
}

.logo {
    height: 70px;
}

</style>