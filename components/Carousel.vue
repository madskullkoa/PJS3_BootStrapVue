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

      <b-carousel-slide img-src="https://i.picsum.photos/id/871/1024/480.jpg?hmac=L152ncbh1idw0TYR7sDxYVditH_sHgzbKqpnwQec8vU">
      </b-carousel-slide>

      <b-carousel-slide img-src="https://i.picsum.photos/id/574/1024/480.jpg?hmac=NuAPCmTV3C1FGzGf62l_9iZD_01kmiwd9u9hUhSgbxM">
      </b-carousel-slide>

      <b-carousel-slide img-src="https://i.picsum.photos/id/588/1024/480.jpg?hmac=P5YW92km4DsLCLsv77a5SBh4YZO6HyePc17kvrLKCr4">
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