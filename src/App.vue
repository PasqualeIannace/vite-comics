<script>
import NavBar from './components/NavBar.vue'
import Section1 from './components/Section1.vue'
import Section2 from './components/Section2.vue'

export default {
	components: {
		NavBar,
		Section1,
		Section2
	}
}
</script>

<template>
	<!-- header -->
	<NavBar />


	<main>
		<Section1 />
		<Section2 />
	</main>

	<!-- footer -->

</template>

<style scoped>

</style>
