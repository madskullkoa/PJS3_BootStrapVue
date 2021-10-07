<script>
import { Vue } from 'vue'
import { BootstrapVue, BootstrapVueIcons } from 'bootstrap-vue'

Vue.use(BootstrapVue)
Vue.use(BootstrapVueIcons)

</script>

<template>
<body>
  <div id="full-size">
  <NavBar/>
  <ScrollToTopBtn/>
  
  <b-container class="bv-example-row">
  <b-row>
    <b-col class="m-10"><Card/></b-col>
    <b-col><Card/></b-col>
    <b-col><Card/></b-col>
  </b-row>
  <b-row>
    <b-col class="m-10"><Card/></b-col>
    <b-col><Card/></b-col>
    <b-col><Card/></b-col>
  </b-row>
  <b-row>
    <b-col class="m-10"><Card/></b-col>
    <b-col><Card/></b-col>
    <b-col><Card/></b-col>
  </b-row>
  <b-row>
    <b-col class="m-10"><Card/></b-col>
    <b-col><Card/></b-col>
    <b-col><Card/></b-col>
  </b-row>
  </b-container>
  
<Footer/>
</div>

</body>
  
</template>


<script>
import NuxtLogoVue from '../components/NuxtLogo.vue'
  export default {
  components: { ScrollToTopBtn, Testbtt },
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

<script>
import ScrollToTopBtn from '../components/ScrollToTopBtn.vue'
export default {
 components: {
   ScrollToTopBtn
 }

}
</script>

<style>

html,body{ margin:0; padding:0; height:100%; width:100%; }
#full-size{
  height:100%;
  width:100%;
  overflow:hidden; /* or overflow:auto; if you want scrollbars */
}

body {
 background-image: url("https://www.oui.sncf/assets/media/2019-08/istock-fabrice-cabaud.jpg");
 background-position: center center;
 background-repeat: no-repeat;
 background-attachment: fixed;
 background-size: cover;
 background-color: #464646;
}
</style>