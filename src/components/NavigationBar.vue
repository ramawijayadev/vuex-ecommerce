<template>
	<nav class="navbar navbar-expand-lg bg-light">
		<div class="container">
			<router-link class="navbar-brand" to="/">Vuex</router-link>
			<button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent"
				aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
				<span class="navbar-toggler-icon"></span>
			</button>
			<div class="collapse navbar-collapse" id="navbarSupportedContent">
				<ul class="navbar-nav me-auto mb-2 mb-lg-0">
					<li class="nav-item">
						<router-link class="nav-link" aria-current="page" to="/" active-class="active-link">Home</router-link>
					</li>
					<li class="nav-item">
						<router-link class="nav-link" to="/about" active-class="active-link">About</router-link>
					</li>
				</ul>
				<form class="d-flex" role="search">
					<input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
					<button class="btn btn-outline-success" type="submit">Search</button>
				</form>
			</div>
		</div>
	</nav>
</template>

<script>
export default {
	name: 'NavigationBar',
}
</script>

<style scoped>
.active {
	color: #42b983;
}

.exact-active-link {
    color: #42b983;
    font-weight: bold;
}
</style>