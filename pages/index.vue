<template>
<body>
  <div id="full-size">
    
  <div style="margin-top: 7em; background-color: red;">
    <NavBar/>
  </div>

  <b-container class="bv-example-row" style="min-width: 100%; height: 50rem; margin-top: 200px; display-flex; flex-direction: row">

    <b-row style="width: 1596px">

      <b-col class="section1a vertical-line">

        <div style="background-color: red; margin-bottom: 2rem; border-radius: 25px 30px 0 25px; width: 75%; display: flex; flex-direction: row; align-items: center; justify-content: center;">
          <b-img src="https://images-eu.ssl-images-amazon.com/images/I/41wkG24yDkL.png" class="img-form"></b-img>
          <span style="font-size: 20px">Météo</span>
        </div>

        <div>
          <b-img src="https://lh3.googleusercontent.com/proxy/U5UBO9eWAcX1EBKjLjyj7VPd4UUYMEGvReJq599ry17HnwXY083Ir15bGRCmm4RgWfmrDsClESspZ56q1n0rZ_srzm0nmq1AjRZs"
          style="border-radius: 10px; width: 250px;"
          fluid alt="Responsive image"></b-img>
        </div>

      </b-col>

      <b-col class="section1b vertical-line" style="background-color: brown; padding: 20px 0 20px 0;">
        <Carousel/>
      </b-col>

    </b-row>

    <div class="section1a" style="height: 100%">

      <div style="background-color: red; margin-bottom: 2rem; border-radius: 25px 30px 0 25px; width: 75%; display: flex; flex-direction: row; align-items: center; justify-content: center;">
        <b-img src="https://lh3.googleusercontent.com/proxy/KDVUfSJbv2jZpwYAXJW4dlLWMyCbD203FshPVVu-KhHC67n_VubuFeAohCHAcfiSmYPEkcWCpUes32x7G9EvKWSJK3PwUh16KwQZ3JE_krLVBBqpoOXPH0uLvbLRihSzIavFfiKiW-SKyQBcvWLF3dUtUDYzmS6wdBuDPM7uTObwvVs7xJFfkF0vsRcGrslMRQ4xK7Oc6SglOH3clwLsZlM53F6_kxqRFJMty_41rVtw_A"
        flex alt="Responsive image" class="img-form"></b-img>
        <span style="font-size: 20px">News</span>
      </div>

      <div style="display: flex; flex-direction: column;">
        <b-img src="https://www.iledebrehat.fr/wp-content/uploads/2021/07/Scene-de-Brehat.jpg"
        style="width: 150px; filter: drop-shadow(5px 5px 4px #303030); margin-bottom: 30px;"
        fluid alt="Responsive image"></b-img>

        <b-img src="https://www.iledebrehat.fr/wp-content/uploads/2021/07/0001-724x1024.jpg"
        style="width: 150px; filter: drop-shadow(5px 5px 4px #303030);"
        fluid alt="Responsive image">
        </b-img>
      </div>

    </div>

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
  color: white;
  font-family: 'Poppins', sans-serif;
  justify-content: center;
  background-color: #61000f;
  width: 100%;
  display: flex;
  flex-direction: column;
  align-items: center;
}

.section1b {
  height: auto;
}

.vertical-line {
  border-right: 2px solid black;
}

.img-form {
  width: 80px;
  height: auto;
  padding-right: 1em;
}

</style>