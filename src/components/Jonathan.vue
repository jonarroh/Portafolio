<template>
	<div class="home-centrar lg:flex-row">
		<div class="mt-20 text-center sm:align-middle">
			<span class="text-gray-200 text-4xl font-bold"
				>Jonathan Uriel Rodriguez Hernandez</span
			>
			<div>
				<span class="text-gradient-v"> Sotfware Engineer </span>
			</div>
		</div>
		<div class="">
			<div class="clip-path mx-5"></div>
		</div>
	</div>
</template>

<style scoped>
.text-gradient-v {
	font-size: 2.5rem;
	color: transparent;
	font-weight: 900;
	background-image: linear-gradient(0deg, #f93a35, #dada62);
	background-clip: content-box;
	-webkit-background-clip: text;
	-webkit-text-fill-color: transparent;
	background-size: 100% 200%;
	background-position-y: 100%;
	border-radius: 0.4rem;
}

.home-centrar {
	display: flex;
	justify-content: center;
	align-items: center;
	flex-direction: column;
	height: 70vh;
}

.clip-path {
	clip-path: polygon(
		25% 0%,
		75% 0%,
		100% 50%,
		75% 100%,
		25% 100%,
		0% 50%
	);

	background-color: #f93a35;
	width: 320px;
	height: 300px;
}

.log {
	border: #f93a35 solid 1px;
}
</style>
