<template>
	<section>
		<Navbar></Navbar>
		<Jonathan></Jonathan>
		<Redes></Redes>
	</section>
</template>

<script setup lang="ts">
import Navbar from '../components/Navbar.vue';
import Jonathan from '../components/Jonathan.vue';
import Redes from '../components/Redes.vue';
</script>

<style scoped>
section {
	width: 100%;
	height: 100vh;
}
</style>
