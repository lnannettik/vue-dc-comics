<template>
    <header>
        <div class="container text-center top-bar">

            <a href="/">
                <img src="../assets/dc-logo.png" alt="Logo DC small">
            </a>

            <nav>
                <ul>
                    <li>
                        <a href="/">Characters</a>
                    </li>
                    
                    <li>
                        <a href="/">Comics</a>
                    </li>
                    
                    <li>
                        <a href="/">Movies</a>
                    </li>
                    
                    <li>
                        <a href="/">Tv</a>
                    </li>
                    
                    <li>
                        <a href="/">Games</a>
                    </li>
                    
                    <li>
                        <a href="/">Collectibles</a>
                    </li>
                    
                    <li>
                        <a href="/">Video</a>
                    </li>
                    
                    <li>
                        <a href="/">Fans</a>
                    </li>
                    
                    <li>
                        <a href="/">News</a>
                    </li>
                    
                    <li>
                        <a href="/">Shop</a>
                    </li>
                    
                </ul>
            </nav>
        </div>
    </header>
</template>

<script>
export default {
    name: 'Header',

}
</script>

<style scoped lang="scss">

.top-bar {
    display: flex;
    justify-content: space-between;
    background-color: lightgrey;
    height: 80px;
    align-items: center;
}

ul {
    display: flex;    
    list-style: none;
    justify-content: center;
    margin: 3rem 0 4rem;

    a {
        height: 100%;
        padding: 1rem;
        display: inline-block;
        text-decoration: none;
        font-weight: 600;
        color: #000;
        &.active,
        &:hover {
            background: lightblue;
        }

        img {
            height: 100%;
        }
    }   
}

</style>