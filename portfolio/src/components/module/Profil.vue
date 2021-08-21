<template>
    <div id="profil">
        <section class="container">
            <h2 id="Musique">Profil</h2>
            <p>Je suis <span class="shine">Loïc Huvelin</span> et me voici avec ce joli <span class="shine">portfolio</span> pour vous présenter qui je suis et ce que je recherche. Passionné d'informatique et d'électronique, j'ai effectué un BAC Sciences et Technologie de l'Industrie et du Développement Durable (<span class="shine">STI2D</span>). Ce BAC m'a beaucoup plu et j'ai pu découvrir et apprendre à coder. De l'algorithmie, à la programmation en C d'une application par Arduino. J'ai ainsi pu confirmer que cette voie me plaisait définitivement. Par la suite, j'ai opté pour un DUT Génie Électrique et Informatique Industrielle (<span class="shine">GEII</span>). Ces deux années m'ont permis d'appronfondir un maximum la programmation et les différents applications possibles dans le milieu de l'industrie.</p>
            <p>Avec le temps, je me suis intéressé à la programmation web et j'ai décidé d'effectuer une formation accélérée de développeur <span class="shine">fullStack</span>. J'aspire à travailler dans ce domaine et suis actuellement à la recherche d'une <span class="shine">alternance</span>.</p>
        </section>
    </div>
</template>

<script>

export default ({
    name:'Profil'
})
</script>

<style scoped>
p {
    font-size: 2.2rem;
    text-align: justify;
    text-justify: distribute;
    text-indent: 4%;
    color: #fff;

    margin: 4rem;
}
.shine {
    color: rgb(78, 177, 172);
    transition: all 0.5s;
}
.shine:hover {
    transform: scale(1.5); 
    color: #ea8832;
}
section {
    padding-bottom: 0.5rem;
}

</style>
