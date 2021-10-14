<template>
  <vue-weather api-key="<your-open-weather-map-api-key>" units="uk" />
</template>

<script>
  import VueWeather from "vue-weather-widget";

  export default {
    components: {
      VueWeather,
    },
  };
</script>