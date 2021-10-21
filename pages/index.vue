<template>
<body>
  <div id="full-size">
  <div style="margin-top: 7em; background-color: red;">
    <NavBar/>
  </div>
  <b-container class="bv-example-row" style="min-width: 100%; height: 50rem; margin-top: 200px">
  <b-row>
    <b-col class="section1a" style="background-color: white;">
      <div style="background-color: grey; margin-bottom: 2rem; border-radius: 25px 30px 0 25px;">
        <img src="https://freesvg.org/img/Anonymous_simple_weather_symbols_4.png" class="img-meteo "><img/>
        <span style="font-size: 20px">Météo</span>
      </div>
      
      <img src="https://lh3.googleusercontent.com/proxy/U5UBO9eWAcX1EBKjLjyj7VPd4UUYMEGvReJq599ry17HnwXY083Ir15bGRCmm4RgWfmrDsClESspZ56q1n0rZ_srzm0nmq1AjRZs" style="border-radius: 10px;" class=""><img/>

    </b-col>
    <b-col class="section1b" style="background-color: red"><Carousel/></b-col>
    <b-col class="section1a" style="background-color: white"></b-col>
  </b-row>
</b-container>
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
  <b-container><Embed/></b-container>
<Footer/>
</div>

</body>
  
</template>


<script>
  export default {
  components: { },
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

.section1a {
  max-width: 350px;
  height: auto;
  font-family: 'Bebas Neue', cursive;
  font-family: 'Poppins', sans-serif;
  justify-content: center;
}

.section1b {
  height: auto;
}

.vertical-line {
  border-right: 4px solid red;
}

.img-meteo {
  width: 100px;
  height: auto;
}
</style>