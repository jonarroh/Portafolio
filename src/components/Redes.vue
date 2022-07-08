<template>
	<div
		class="flex justify-center flex-col font-bold items-center mt-4"
	>
		<div class="text-slate-50 text-lg text-center w-full">
			Contactos:
		</div>
		<div class="card-redes relative flex flex-row justify-around">
			<img src="/signo-de-github.png" alt="icon">
			<img src="/signo-de-github.png" alt="icon" >
			<img src="/signo-de-github.png" alt="icon" >
			<img src="/signo-de-github.png" alt="icon" >
		</div>
	</div>
</template>

<style>
.card-redes {
	display: flex;
	justify-content: center;
	margin: 20px;
	padding: 20px;
	flex-direction: column;
	background-color: #e0dcee;
	box-shadow: 0 10px 15px -3px rgb(0 0 0 / 0.1),
		0 4px 6px -4px rgb(0 0 0 / 0.1);
	width: 90vw;
	border-radius: 10px;
}

img {
	width: 50px;
	height: 50px;
}
img:hover {
	cursor: pointer;
	transform: scale(1.2);
}
</style>
