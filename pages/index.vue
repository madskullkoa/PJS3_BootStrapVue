<template>

<div>
<div class="page">
  <NavBar/>
  
  <!-- <b-container class="bv-example-row">
  <b-row>
    <b-col class="m-10"><Card/></b-col>
    <b-col><Card/></b-col>
    <b-col><Card/></b-col>
  </b-row>
</b-container> -->

</div>
</div>

</template>

<script>
import NuxtLogoVue from '../components/NuxtLogo.vue'
  export default {
    data() {
      return {
        title: 'Commune d\'Île-de-Bréhat'
      }
    },
    head() {
      return {
        title: this.title,
        meta: [
          // hid is used as unique identifier. Do not use `vmid` for it as it will not work
          {
            hid: 'description',
            name: 'description',
            content: 'My custom description'
          }
        ]
      }
    }
  }
</script>
<style>

  body {
 background-image: url("https://www.oui.sncf/assets/media/2019-08/istock-fabrice-cabaud.jpg");
 background-position: center center;
 background-repeat: no-repeat;
 background-attachment: fixed;
 background-size: cover;
 background-color: #464646;
}
</style>