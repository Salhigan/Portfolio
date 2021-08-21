<template>
    <div id="footer">
        <h2>Contact</h2>
        <nav>
            <a href="#">Loïc Huvelin</a>
            <a href="mailto:loic.huv@gmail.com">Mail</a>
            <a href="tel:0652279047">Téléphone</a>
            <a href="#"><img src="../../../public/img/Small-logo.png" alt="Small-logo"></a>
            <a href="https://soundcloud.com/salhigan" target="_blank">Soundcloud</a>
            <a href="https://github.com/Salhigan" target="_blank">Github</a>
            <a href="#pixel">Pixel Art</a>
        </nav>
    </div>
</template>

<script>

export default ({
    name:'Footer'
})
</script>

<style scoped>
#footer {
    background-color: rgb(78, 177, 172);
}
nav {
    display: flex;
    justify-content: space-between;
    align-items: center;

    padding: 1rem;
}
nav a {
    flex: 1;
    padding: 1rem;
    border-top: 3px solid #ea883200;
    border-bottom: 3px solid #ea883200;

    transition: all 0.5s;
    
    text-decoration: none;
    color: #fff;
    font-size: 4rem;
    font-family: 'Righteous', cursive;
}
nav a:hover {
    border-top: 3px solid #ea8832;
    border-bottom: 3px solid #ea8832;
}
</style>