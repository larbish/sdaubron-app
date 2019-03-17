<template>
	<section>
		<b-carousel id="carousel1"
					:interval="4000"
					controls
					height="700"
					v-model="slide"
					@sliding-start="onSlideStart"
					@sliding-end="onSlideEnd"
		>
			<!-- Photo by How-Soon Ngu on Unsplash -->
			<!-- Photo by Nick Wilkes on Unsplash -->
			<b-carousel-slide img-src="~/assets/images/home-slide-1.jpg"></b-carousel-slide>
			<b-carousel-slide  img-src="~/assets/images/home-slide-2.jpg"></b-carousel-slide>
		</b-carousel>

		<div class="container pb-0">
            <div class="bg-white my-md-5 mt-3 p-3">
                <div class="row">
                    <div class="col-md-2 col-4">
                        <img class="w-100 h-auto" src="/sandrine_daubron.jpg" alt="sandrine_daubron">                    
                    </div>
                    <div class="col-md-10 col-8">
                        <div class="d-flex justify-content-between">
                            <h1>Pédicure Podologue Orsay</h1>
							<div class="d-none d-md-block">
								<a class="btn py-2 px-4 text-20-xs d-flex align-items-center" target="_blank" rel="noreferrer" href="https://www.doctolib.fr/pedicure-podologue/orsay/sandrine-daubron/">
									<span>Prendre rendez-vous</span>
									<fa class="ml-2" :icon="['fa', 'angle-right']" />
								</a>
							</div>
                        </div>
                        <h2 class="text-20-xs text-bold">Sandrine Daubron</h2>
                        <p class="text-muted d-none d-md-block">
                            Je vous accueille dans mon cabinet au 1 rue des Mésanges à Orsay. 
                            N'hésitez pas à me contacter pour une urgence directement par téléphone au 01 69 28 07 65.
                            Je me déplace à domicile le jeudi sur les communes d'Orsay, Bures et Villebon.
                        </p>
                    </div>
                </div>

				<!-- ONLY MOBILE -->
				<div class="d-block d-md-none mt-3">
					<p class="text-muted">
						Je vous accueille dans mon cabinet au 1 rue des Mésanges à Orsay. 
						N'hésitez pas à me contacter pour une urgence directement par téléphone au 01 69 28 07 65.
						Je me déplace à domicile le jeudi sur les communes d'Orsay, Bures et Villebon.
					</p>
					<a class="mt-4 btn py-2 px-4 text-20-xs d-flex align-items-center d-block d-md-none" target="_blank" rel="noreferrer" href="https://www.doctolib.fr/pedicure-podologue/orsay/sandrine-daubron/">
						<span>Prendre rendez-vous</span>
						<fa class="ml-2" :icon="['fa', 'angle-right']" />
					</a>
				</div>

            </div>
		</div>

		<div class="mt-4 mt-md-0 mb-md-5 mb-3 container-fluid">
			<div class="row">
				<no-ssr>
					<div class="col-md-3 col-12 py-md-0 px-5 mb-md-0 mb-5" v-for="job in jobs" :key="job.name">
						<JobBlock :job="job" ></JobBlock>
					</div>
				</no-ssr>
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
				{ name: 'podologie', url: '/podologie/semelles' },
				{ name: 'pedicure', url: '/pedicurie/soin' },
				{ name: 'posturologie', url: '/posturologie' },
				{ name: 'reflexologie', url: '/reflexologie' }
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
.container {
	min-height: 0px !important;
}
</style>
