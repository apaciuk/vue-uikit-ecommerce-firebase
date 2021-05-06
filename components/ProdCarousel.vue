<template>
<div class="uk-section uk-section-muted uk-margin-top">
<VueSlickCarousel v-bind="slickOptions">
      <div v-for="i in 5" :key="i" class="img-wrapper">
        <img :src="`./${i}-slider.jpg`" />
      </div>
</VueSlickCarousel>
</div>
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

<style scoped>
.img-wrapper img {
  margin: auto;
  width: 924px;
  height: 470px;
  background-image: linear-gradient(gray 100%, transparent 0);
}
</style>
   