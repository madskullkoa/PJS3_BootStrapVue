<template>
  <div>
    <b-carousel
      class="dims"
      id="carousel-1"
      v-model="slide"
      :interval="4000"
      controls
      indicators
      background="#ababab"
      img-width="1024"
      img-height="480"
      style="text-shadow: 1px 1px 2px #333;"
      @sliding-start="onSlideStart"
      @sliding-end="onSlideEnd"
      
    >

      <b-carousel-slide img-src="https://i.picsum.photos/id/278/1024/480.jpg?hmac=4xBvmOHF41FLqMfx52MFM9ZNSt3egopUhLl7S3Od18c">
      </b-carousel-slide>

      <b-carousel-slide img-src="https://i.picsum.photos/id/50/1024/480.jpg?hmac=iY9VA0gPycmEiPh8yUYRWqTsqqfNA63dpHtLYpfyvDw">
      </b-carousel-slide>

      <b-carousel-slide img-src="https://i.picsum.photos/id/337/1024/480.jpg?hmac=Nd3QMR5do0Fx-2_-T8FhidyWAZuLP9SZnPw8NSYiRgo">
      </b-carousel-slide>

      <b-carousel-slide img-src="https://i.picsum.photos/id/867/1024/480.jpg?hmac=uj1dSudxsbCP79EPryobzMPoCuoq7ikXbwiiYQel_Gc">
      </b-carousel-slide>
      

    </b-carousel>
  </div>
</template>

<script>
  export default {
    data() {
      return {
        slide: 0,
        sliding: null
      }
    },
    methods: {
      onSlideStart(slide) {
        this.sliding = true
      },
      onSlideEnd(slide) {
        this.sliding = false
      }
    }
  }
</script>

<style>
.dims{
width: 100%;
height: 100%;
}
</style>