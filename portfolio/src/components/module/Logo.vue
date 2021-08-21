<template>
    <div id="logo">
        <section id="mouseTarget" class="container">
            <img class="layer" data-speed="1" src="../../../public/img/Big-logo-orange.png" alt="Big-logo">
            <img class="layer" data-speed="3" src="../../../public/img/Big-logo-orange.png" alt="Big-logo">
            <img class="layer" data-speed="5" src="../../../public/img/Big-logo-orange.png" alt="Big-logo">
            <img class="layer" data-speed="7" src="../../../public/img/Big-logo-orange.png" alt="Big-logo">
            <img class="layer" data-speed="9" src="../../../public/img/Big-logo-orange.png" alt="Big-logo">
            <img class="layer" data-speed="11" src="../../../public/img/Big-logo-orange.png" alt="Big-logo">
            <img class="layer" data-speed="2" src="../../../public/img/Big-logo-turquoise.png" alt="Big-logo">
            <img class="layer" data-speed="4" src="../../../public/img/Big-logo-turquoise.png" alt="Big-logo">
            <img class="layer" data-speed="6" src="../../../public/img/Big-logo-turquoise.png" alt="Big-logo">
            <img class="layer" data-speed="8" src="../../../public/img/Big-logo-turquoise.png" alt="Big-logo">
            <img class="layer" data-speed="10" src="../../../public/img/Big-logo-turquoise.png" alt="Big-logo">
            <img class="layer" data-speed="12" src="../../../public/img/Big-logo-turquoise.png" alt="Big-logo">
            <div>
                <img class="layer" src="../../../public/img/Big-logo.png" alt="Big-logo">
            </div>
        </section>
    </div>
</template>

<script>
export default ({
    name:'Logo'
})

document.addEventListener("mousemove", parallax);
function parallax(e){
    this.querySelectorAll(".layer").forEach(layer => {
        const speed = layer.getAttribute("data-speed");

        const x = (window.innerWidth - (e.pageX - window.innerWidth/2)*speed)/40;
        const y = (window.innerHeight - (e.pageY - window.innerHeight/2)*speed)/40;

        layer.style.transform = `translateX(${x}px) translateY(${y}px)`;
    });
}

</script>

<style scoped>
section {
    position: relative;
    height: 60vh;
    overflow: hidden;
    display: flex;
    justify-content: center;
    align-items: center;
}

section div {
    position: relative;
}

section > img {
    position: absolute;

    object-fit: cover;
}
</style>
