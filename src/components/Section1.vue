<script>
export default {
	props: {
		products: Object
	},

	mounted() {
		console.log("Section 1!");
	}
}
</script>

<template>
	<div class="jumbo">
		<img src="/jumbotron.jpg" alt="">
	</div>

	<div class="productsBg">
		<div class="desktop products">
			<div class="info">
				CURRENT SERIES
			</div>

			<div v-for="product in products" class="card">
				<img :src="product.thumb" alt="">
				<p class="upperCase">{{ product.series }}</p>
				<span>{{ product.price }}</span>
			</div>

			<div class="more">
				<div class="moreBtn">
					LOAD MORE
				</div>
			</div>
		</div>
	</div>
</template>

<style scoped>
div {
	color: white;
	background-color: #1C1C1C;
	height: 10vh;
}

.jumbo {
	height: 18em;
}

.jumbo img {
	width: 100%;
	height: 100%;
	object-fit: cover;
	object-position: top;
}

.productsBg {
	background-color: #1C1C1C;
	height: auto;
}
.products {
	display: flex;
	flex-wrap: wrap;
	padding: 3em 4em 0 4em;
	height: 35em;
	position: relative;
}

.card {
	width: calc(100% / 6);
}

img {
    width: 8.5em;
    height: 8.5em;
    object-fit: cover;
    object-position: top;
}

.card p {
	font-size: 0.7em;
}

.info {
	position: absolute;
    background-color: #0082F9;
    top: -23px;
    height: 2em;
    padding: 0.5em 1em;
    font-weight: bold;
    font-size: 1.3em;
}

.more {
    display: flex;
    width: 100vw;
    height: 3em;
    justify-content: center;
    align-items: center;
}
.moreBtn {
    background-color: #0082F9;
    height: 2em;
    width: 10em;
    padding: 0.5em 1.9em;
    font-size: 0.9em;
	font-weight: bold;
}

span {
	font-size: 0.7em;
}
</style>
