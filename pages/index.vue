<template>
  <body>
    <div id="full-size">
      <div style="margin-top: 7em; background-color: red;">
        <NavBar />
      </div>
      <b-container
        class="bv-example-row"
        style="min-width: 100%; height: 50rem; display-flex; flex-direction: row"
      >
        <b-row>
          <b-col class="section1a vertical-line">
            <div
              style="background-color: dodgerblue; margin-bottom: 2rem; border-radius: 25px 30px 0 25px; width: 75%; display: flex; flex-direction: row; align-items: center; justify-content: center;"
            >
              <b-img
                src="https://images-eu.ssl-images-amazon.com/images/I/41wkG24yDkL.png"
                class="img-form1"
              ></b-img>
              <span style="font-size: 20px">Météo</span>
            </div>

            <div>
              <b-img
                src="https://www.google.com/maps/vt/data=RHTX4ZY6NeRMNNyO7CVFX9T79Ah-fNC1_eHNrIGLQaPq7sswuxmYDu0WE7rPR_-UrEOVR_XAg8G8eVrNduxPSK03jvnHXNhah17eLPrP0imZrdRbLWT3isFeepbBGhve-zRu7oZ1xcwzv_hSW3ArkNaZRfASlwBSmJ1JAa4X-tzmC-Z5sTj-YgIjFeIaF__a7brlMPVg93QM5JVT8R_2ul3rW5gzuln7-Gg8ixVdofXlbw"
                style="border-radius: 10px; width: 250px;"
                fluid
                alt="Responsive image"
              ></b-img>
            </div>
          </b-col>

          <b-col
            class="section1b vertical-line"
            style="background-color: dodgerblue; padding: 20px 0 20px 0;"
          >
            <Carousel />
          </b-col>

          <b-col class="section1a">
            <div
              style="background-color: dodgerblue; margin-bottom: 2rem; border-radius: 25px 30px 0 25px; width: 75%; display: flex; flex-direction: row; align-items: center; justify-content: center;"
            >
              <b-img
                src="https://cdn.pixabay.com/photo/2012/04/01/17/40/paper-23700_960_720.png"
                flex
                alt="Responsive image"
                class="img-form2"
              ></b-img>
              <span style="font-size: 20px">News</span>
            </div>

            <div style="display: flex; flex-direction: column;">
              <b-img
                src="https://www.iledebrehat.fr/wp-content/uploads/2021/07/Scene-de-Brehat.jpg"
                style="width: 150px; filter: drop-shadow(5px 5px 4px #303030); margin-bottom: 30px;"
                fluid
                alt="Responsive image"
              ></b-img>

              <b-img
                src="https://www.iledebrehat.fr/wp-content/uploads/2021/07/0001-724x1024.jpg"
                style="width: 150px; filter: drop-shadow(5px 5px 4px #303030);"
                fluid
                alt="Responsive image"
              >
              </b-img>
            </div>
          </b-col>
        </b-row>

        <b-row>
          <b-col
            style="background-color: lightblue; font-family: 'Poppins', sans-serif;"
            class="vertical-line"
          >
            <h2>
              <b><u>Histoire de l’île: </u></b>
            </h2>
            <br /><br />
            <h4>
              Du paléolithique à nos jours, découvrez l’histoire de l’île de
              Bréhat, premier port de la baie de Saint Brieuc jusqu’à la fin du
              XVIIIème siècle, premier site classé de France en 1907.
            </h4>
            <br />
            <v-btn
              elevation="2"
              style="float: right; background-color: deepskyblue;"
              >En savoir plus</v-btn
            >
          </b-col>

          <b-col class="section1a"> </b-col>
        </b-row>

        <b-row>
          <b-col
            style="background-color: deepskyblue; font-family: 'Poppins', sans-serif;"
            class="vertical-line"
          >
            <h2
              style="text-align: center; margin-top: 20px; margin-bottom: 20px;"
            >
              <b><u>DERNIERS ARTICLES </u></b>
            </h2>
            <br />
            <div style="display: flex; justify-content: space-around;">
              <Card />
              <Card />
              <Card />
            </div>
          </b-col>

          <b-col class="section1a"> </b-col>
        </b-row>

        <b-row>
          <b-col
            class="vertical-line"
            style="display: flex; justify-content: space-around; flex-direction: row; align-items: center;"
          >
            <Embed />

            <div
              style="display: flex; justify-content: space-around; flex-direction: column;"
            >

              <div style="display: flex; justify-content: space-around;">
                <b-img
                  src="https://www.oui.sncf/assets/media/2019-08/istock-fabrice-cabaud.jpg"
                  style="margin: 5px 5px 5px 5px; width: 250px; height: 188px;"
                ></b-img>
                <b-img
                  src="https://upload.wikimedia.org/wikipedia/commons/thumb/b/b6/Image_created_with_a_mobile_phone.png/250px-Image_created_with_a_mobile_phone.png"
                  style="margin: 5px 5px 5px 5px; width: 250px; height: 188px;"
                ></b-img>
              </div>

              <div style="display: flex; justify-content: space-around;">
                <b-img
                  src="https://upload.wikimedia.org/wikipedia/commons/thumb/b/b6/Image_created_with_a_mobile_phone.png/250px-Image_created_with_a_mobile_phone.png"
                  style="margin: 5px 5px 5px 5px; width: 250px; height: 188px;"
                ></b-img>
                <b-img
                  src="data:image/jpeg;base64,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"
                  style="margin: 5px 5px 5px 5px; width: 250px; height: 188px;"
                ></b-img>
              </div>

            </div>
          </b-col>
          <b-col class="section1a"></b-col>
        </b-row>
        <ScrollToTopBtn />
      </b-container>
      <b-container style="height:1500px"></b-container>
      <Footer />
    </div>
  </body>
</template>

<script>
export default {
  components: {},
  data() {
    return {
      title: "Commune d'Île-de-Bréhat"
    };
  },
  head() {
    return {
      title: this.title,
      meta: [
        {
          hid: "description",
          name: "description",
          content: "My custom description"
        }
      ]
    };
  }
};
</script>

<style>
html,
body {
  margin: 0;
  padding: 0;
  height: 100%;
  width: 100%;
}
#full-size {
  height: 100%;
  width: 100%;
  overflow: hidden;
}

body {
  background-position: center center;
  background-repeat: no-repeat;
  background-attachment: fixed;
  background-size: cover;
}

.section1b {
  height: auto;
}

.section1a {
  max-width: 350px;
  color: white;
  font-family: "Poppins", sans-serif;
  justify-content: center;
  background-color: navy;
  width: 100%;
  display: flex;
  flex-direction: column;
  align-items: center;
}

.vertical-line {
  border-right: 2px solid black;
}

.img-form1 {
  width: 80px;
  height: auto;
  padding-right: 1em;
}

.img-form2 {
  width: 30px;
  height: auto;
  margin: 0.8em 0.8em 0.8em 0.8em;
}
</style>
