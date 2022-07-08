<template>
	<section>
		<Navbar></Navbar>
	</section>
</template>

<script setup lang="ts">
import Navbar from '../components/Navbar.vue';
</script>

<style scoped>
:root {
	--backgroud-g: #311558;
}

section {
	width: 100%;
	height: 100vh;
	background-color: rgb(19, 18, 58);
}
</style>
