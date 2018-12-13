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
	-webkit-filter: sepia(100%);
	filter: sepia(100%);
	-webkit-transition: .3s ease-in-out;
    transition: .3s ease-in-out;

    position: relative;
    text-align: center;
    color: white;
}

.job-img:hover {
	-webkit-filter: sepia(0);
    filter: sepia(0);
    -webkit-transform: scale(0.75);
	transform: scale(0.85);
}
</style>
