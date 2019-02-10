<template>
  <section class="w-100">
  	<a class="" href="#">
        <img class="w-100 job-img" :src="imgUrl" :alt="jobName">
        <h2 class="text-position text-uppercase text-bold">{{ jobName }}</h2>
    </a>
  </section>
</template>

<script>
export default {
    props:  ['jobName'],
    data() {
        return {
            imgUrl: `/job-${this.jobName}.jpg`
        }
    }
    
}
</script>

<style>

.job-img {
	-webkit-filter: grayscale(80%);
	filter: grayscale(80%);
	-webkit-transition: .3s ease-in-out;
    transition: .3s ease-in-out;

    position: relative;
    text-align: center;
    color: white;
}

.job-img:hover {
	-webkit-filter: grayscale(50%);
    filter: grayscale(50%);
    -webkit-transform: scale(0.75);
	transform: scale(0.85);
}
</style>
