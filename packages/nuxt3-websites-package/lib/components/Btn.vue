<template>
	<button>
		<slot></slot>
	</button>
</template>

<style  scoped>
button { 
	border: none;
	padding: 10px 20px;
	background: blue;
	color: white;
	border-radius: 5px;
	/* some other stuff */
}
</style>