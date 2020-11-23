<template>
	<header>
		<ul class="nav-items">
			<li>
				<nuxt-link to="/">Home</nuxt-link>
			</li>
			<li>
				<nuxt-link to="/products">Products</nuxt-link>
			</li>
		</ul>
	</header>
</template>

<style  scoped>
header {
	height: 60px;
	width: 100%;
	display: flex;
	justify-content: center;
	align-items: center;
	background-color: rgb(251, 106, 96);
}
.nav-items {
	list-style: none;
	margin: 0;
	padding: 0;
	display: flex;
	justify-content: space-around;
	align-items: center;
	width: 80%;
}

.nav-items a:hover,
.nav-items a:active {
	color: rgb(255, 255, 255);
	transition: all ease 300ms;
}
</style>