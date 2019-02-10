<template>
	<section>
		<b-carousel id="carousel1"
					:interval="4000"
					controls
               		indicators
					height="700"
					v-model="slide"
					@sliding-start="onSlideStart"
					@sliding-end="onSlideEnd"
		>
			<!-- Photo by How-Soon Ngu on Unsplash -->
			<!-- Photo by Nick Wilkes on Unsplash -->
			<b-carousel-slide img-src="~/assets/images/home-slide-1.jpg">
			 	<h1 class="mb-5">Hello world!</h1>
			 </b-carousel-slide>
			<b-carousel-slide  img-src="~/assets/images/home-slide-2.jpg"></b-carousel-slide>
		</b-carousel>

		<div class="text-center my-5">
			<h1 class="mb-3">1 rue des mésanges - 91 400 Orsay</h1>
			<a class="btn btn-large py-3 px-5 text-20-xs" target="_blank" href="https://www.doctolib.fr/">
				<span>Prendre rendez-vous</span>
				<fa class="ml-2" :icon="['fa', 'angle-right']" />
			</a>
		</div>
		<div class="my-5 container-fluid">
			<div class="row">
				<div class="col-md-3 col-12 py-3 py-md-0 px-4" v-for="job in jobs">
					<JobBlock v-bind:jobName=job.name></JobBlock>	
				</div>
			</div>
		</div>
	</section>
</template>

<script>
import JobBlock from '~/components/job-block.vue';

export default {
	components: {
		JobBlock
	},

	data () {
		return {
			slide: 0,
			sliding: null,
			jobs: [
				{ name: 'podologie' },
				{ name: 'pedicure' },
				{ name: 'posturologie' },
				{ name: 'reflexologie' }
			]
		}
	},

	methods: {
		onSlideStart (slide) {
		this.sliding = true
		},
		onSlideEnd (slide) {
		this.sliding = false
		}
	}
}
</script>

<style>
.btn {
	border-radius: 35px !important;
	color: white;
	background-color: black;
}
.btn:hover {
	border: 1px solid black;
	color: black;
	background-color: white;
}
.btn:focus {
	box-shadow: none;
}
</style>
