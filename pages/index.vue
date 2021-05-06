<template>
<VueSlickCarousel v-bind="slickOptions">
      <div v-for="i in 5" :key="i" class="img-wrapper">
        <img :src="`./${i}-slider.jpg`" />
      </div>
</VueSlickCarousel>
</template>
<script>
export default {
data() {
    return {
      slickOptions: {
        slidesToShow: 3,
        arrows: false
      }
    }
  }
}
</script>

<style>
.img-wrapper img {
  margin: auto;
  width: 924px;
  height: 470px;
  background-image: linear-gradient(gray 100%, transparent 0);
}
</style>
   



