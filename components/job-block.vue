<template>
  <section>
  	<div>
        <nuxt-link class="circle plus-position d-flex align-items-center justify-content-center" :to="job.url">
            <fa class="text-black" :icon="['fa', 'plus']" />
        </nuxt-link>
        <img class="w-100 job-img" :src="imgUrl" :alt="job.name">
        <h2 class="title text-position text-uppercase text-bold">{{ job.name }}</h2>
    </div>
  </section>
</template>

<script>
export default {
    props: {
        job: {
            type: Object
        }
    },

    data() {
        return {
            imgUrl: `/job-${this.job.name}.jpg`
        }
    }
    
}
</script>

<style>
.text-position {
    color: black;
    font-size: 22px !important;
    font-weight: bold;
    position: absolute;
    top: 1%;
    left: 16%;
    @media (min-width: 992px) { 
        top: 1%;
        left: 12%;
    }
}

.circle {
    z-index: 100;
    text-align: center;
    width: 35px;
    height: 35px;
    line-height: 27px;
    background-color: black;
    border-radius: 35px;
}

.circle:hover {
    -webkit-transform: scale(0.85);
    transform: scale(0.85);
}

.plus-position {
    color: black;
    font-size: 30px;
    font-weight: bold;
    position: absolute;
    color: white !important;
    top: 70%;
    left: 45%;
    @media (min-width: 992px) { 
        top: 70%;
        left: 50%;
    }
}


.job-img {
	-webkit-filter: grayscale(100%);
	filter: grayscale(100%);
	-webkit-transition: .3s ease-in-out;
    transition: .3s ease-in-out;

    position: relative;
    text-align: center;
    color: white;
}

.job-img:hover, .circle:hover ~ .job-img {
	-webkit-filter: grayscale(50%);
    filter: grayscale(50%);
    -webkit-transform: scale(0.85);
    transform: scale(0.85);
}

.title {
    color: white;
    -webkit-transition: .3s ease-in-out;
    transition: .3s ease-in-out;
}

.job-img:hover + .title, .circle:hover ~ .title {
    color: black !important;
    -webkit-transition: .3s ease-in-out;
    transition: .3s ease-in-out;
}

</style>
