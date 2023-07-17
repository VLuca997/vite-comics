<script>
import HeaderLogoComponent from '../components/HeaderLogoComponent.vue';
// my-component.js
export default {
	data() {
		return 
	},
	components:{
    HeaderLogoComponent,
}
}
</script>
<!-- STRUTTURA NAVBAR HEADER -->
<template>
	<div>
		<nav class="navbar navbar-expand-lg ">
			
			<div class="container-fluid d-flex">

				<a class="navbar-brand text-danger" href="#"><HeaderLogoComponent /></a>

				<button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">

					<span class="navbar-toggler-icon"></span>

				</button>
				
				<div class="collapse navbar-collapse justify-content-end " id="navbarSupportedContent">

					<ul class="navbar-nav">
						<!-- cicliamo 10 li  -->
						<li v-for="i in 10" :key="i" class="nav-item">

							<a class="nav-link active" aria-current="page" href="#">Home</a>

						</li>
						
					</ul>
					
				</div>
			</div>
		</nav>
	</div>	
</template>

<style lang="scss" >

	img{
		height: 70px;
	}
</style>