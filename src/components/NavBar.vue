<script>
export default {
	data() {
		return {
			menuLinks : [
				{
					text: "CHARACTERS",
					url: "#",
				},
				{
					text: "COMICS",
					url: "#",
				},
				{
					text: "MOVIES",
					url: "#",
				},
				{
					text: "TV",
					url: "#",
				},
				{
					text: "GAMES",
					url: "#",
				},
				{
					text: "COLLECTIBLES",
					url: "#",
				},
				{
					text: "VIDEOS",
					url: "#",
				},
				{
					text: "FANS",
					url: "#",
				},
				{
					text: "NEWS",
					url: "#",
				},
				{
					text: "SHOP",
					url: "#",
				}
			]
		}
	},

	mounted() {
		console.log("Nav bar ok!");
	}
}


</script>

<template>
	<header>
		<div class="logo">
			<a href="#home">
				<img src="\dc-logo-bg.png" alt="">
			</a>
		</div>

		<nav>
			<ul>
				<li v-for="link in menuLinks">
					<a :href="link.url">
						{{ link.text }}
					</a>
				</li>
			</ul>
		</nav>
	</header>
</template>

<style scoped>
	header {
		padding: 0 4em;
		display: flex;
		align-items: center;
		height: 10vh;
	}

	.logo {
		width: 100%;
	}

	.logo a {
		display: inline-block;
	}

	img {
		width: 7vh;
	}

	li {
		display: inline;
		padding: 1em;
	}

	li a {
		color: #1C1C1C;
		text-decoration: none;
	}
</style>
