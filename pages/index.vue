<template>
<body>
  <div id="full-size">
    
  <NavBar/>
  <ScrollToTopBtn/>
  
  <b-container class="bv-example-row">
    <Carousel/>
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
  <b-container><Embed/></b-container>
<Footer/>
</div>

</body>
  
</template>


<script>
  export default {
  components: { ScrollToTopBtn, Testbtt, Carousel },
    data() {
      return {
        title: 'Commune d\'Île-de-Bréhat'
      }
    },
    head() {
      return {
        title: this.title,
        meta: [
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
import Carousel from '../components/Carousel.vue'
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
  overflow:hidden;
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