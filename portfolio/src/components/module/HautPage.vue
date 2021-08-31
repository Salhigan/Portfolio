<template>
    <div id="HautPage">
        <div class="carre">
            <a href="#header"></a>
        </div>
    </div>
</template>

<script>

export default ({
    name:'HautPage'
})
</script>

<style scoped>
#HautPage {
    position: sticky;
    top: 0;
    z-index: 10;
}
.carre {
    background: rgba(0, 0, 0, 0.5);
    width: 80px;
    height: 80px;

    margin: auto;
}
a {
    color:white;
	display: block;
    
    text-decoration: none;
	position: relative;
	
    top: 35%;
    left: 25%;

	transition: all .3s ease-out;
}
a:before{
	content: '▲';
	font-size: 5rem;
	position: absolute;


	margin-left: -4.3rem;
	width: 4.5rem;
	height: 3rem;
	line-height: 1rem;

	transition:transform .5s;
}
a:hover{
	color:#ea8832;
}
.carre:hover a:before{
	transform: rotate(-360deg) scale(1.4);
}
</style>