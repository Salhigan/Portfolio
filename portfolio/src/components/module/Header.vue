<template>
    <div id="header">
        <nav>
            <a href="#"><img src="../../../public/img/Small-logo.png" alt="Small-logo"></a>
            <div>
                <a href="#logo">Logo</a>
                <a href="#profil">Profil</a>
                <a href="#music">Musique</a>
                <a href="#footer">Contact</a>
            </div>
        </nav>
    </div>
</template>

<script>

export default ({
    name:'Header'
})
</script>

<style scoped>
nav {
    display: flex;
    justify-content: space-between;
    align-items: center;

    padding: 1rem;

    background-color: rgb(78, 177, 172);
}
nav div a {
    padding: 2rem;
    border-top: 4px solid #ea883200;
    border-bottom: 4px solid #ea883200;
    transition: all 0.5s;
    
}
nav div a:hover {
    border-top: 4px solid #ea8832;
    border-bottom: 4px solid #ea8832;
}
nav a {
    text-decoration: none;
    color: #fff;
    font-size: 4rem;
    font-family: 'Righteous', cursive;
}
</style>