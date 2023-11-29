<script>
export default {
	data() {
		return {
            prodotti: [
                {
                    text: "DIGITAL COMICS",
                    url: "#",
                    src: "buy-comics-digital-comics.png"
                },
                {
                    text: "DC MERCHANDISE",
                    url: "#",
                    src: "buy-comics-merchandise.png"
                },
                {
                    text: "SUBSCRIPTION",
                    url: "#",
                    src: "buy-comics-subscriptions.png"
                },
                {
                    text: "COMIC SHOP LOCATOR",
                    url: "#",
                    src: "buy-comics-shop-locator.png"
                },
                {
                    text: "DC POWER VISA",
                    url: "#",
                    src: "buy-dc-power-visa.svg"
                }
            ]
        }
	},

	mounted() {
		console.log("Section 2!");
	}
}


</script>

<template>
	<div class="sectionBg">
        <div class="desktop section">
            <div class="product" v-for="prodotto in prodotti">
            <a :href="prodotto.url">
                    <div>
                        <img :src="prodotto.src" alt="">
                    </div>
                    <div class="px1">
                        {{ prodotto.text }}
                    </div>
            </a> 
            </div>
        </div>
    </div>
</template>

<style scoped>
    .sectionBg {
        background-color: #0082F9;
    }
    .section {
        color: white;
        background-color: #0082F9;
        height: 15vh;
        padding: 0 4em;
        display: flex;
        align-items: center;
    }

    .product {
        width: calc(100% / 5);
    }

    .product a {
        display: flex;
        align-items: center;
        justify-content: center;
        color: white;
        text-decoration: none;
    }

    img {
        height: 3.5em;
    }
</style>