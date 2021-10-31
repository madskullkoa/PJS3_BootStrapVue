<template>
  <body>
    <div id="full-size">
      <div style="margin-top: 7em;">
        <NavBar />
      </div>
      <b-container
        class="bv-example-row"
        style="min-width: 100%;display-flex; flex-direction: row"
      >
        <b-row>
          <b-col class="section1a vertical-line">
            <div
              style="background-color: red; margin-bottom: 2rem; border-radius: 25px 30px 0 25px; width: 75%; display: flex; flex-direction: row; align-items: center; justify-content: center;"
            >
              <b-img
                src="https://images-eu.ssl-images-amazon.com/images/I/41wkG24yDkL.png"
                class="img-form1"
                style="margin-left: 1em;"
              ></b-img>
              <div class="patterns">
              <svg width="100%" height="100%">
                <defs>
                  <style>
                    @import url("https://fonts.googleapis.com/css?  family=Lora:400,400i,700,700i");
                  </style>
                </defs>

                <rect
                  x="0"
                  y="0"
                  width="100%"
                  height="100%"
                  fill="url(#polka-dots)"
                ></rect>

                <text x="40%" y="60%" text-anchor="middle" style="font-size:30px">
                  Météo
                </text>
              </svg>
            </div>
            </div>

            <div>
              <b-img
                src="https://www.google.com/maps/vt/data=RHTX4ZY6NeRMNNyO7CVFX9T79Ah-fNC1_eHNrIGLQaPq7sswuxmYDu0WE7rPR_-UrEOVR_XAg8G8eVrNduxPSK03jvnHXNhah17eLPrP0imZrdRbLWT3isFeepbBGhve-zRu7oZ1xcwzv_hSW3ArkNaZRfASlwBSmJ1JAa4X-tzmC-Z5sTj-YgIjFeIaF__a7brlMPVg93QM5JVT8R_2ul3rW5gzuln7-Gg8ixVdofXlbw"
                style="border-radius: 10px; width: 250px; margin-bottom: 5px;"
                fluid
                alt="Responsive image"
              ></b-img>
            </div>

            <div>
              <b-img
                src="../weather.PNG"
                style="border-radius: 10px; width: 250px;"
                fluid
                alt="Responsive image"
              ></b-img>
            </div>
          </b-col>

          <b-col
            class="section1b vertical-line"
            style="background-color: #fefee2; padding: 20px 0 20px 0;"
          >
            <Carousel />
          </b-col>

          <b-col class="section1a">
            <div
              style="background-color: red; margin-bottom: 2rem; border-radius: 25px 30px 0 25px; width: 75%; display: flex; flex-direction: row; align-items: center; justify-content: center;"
            >
              <b-img
                src="https://cdn.pixabay.com/photo/2012/04/01/17/40/paper-23700_960_720.png"
                flex
                alt="Responsive image"
                class="img-form2"
                style="margin-left: 2em;"
              ></b-img>
              <div class="patterns">
              <svg width="100%" height="100%">
                <defs>
                  <style>
                    @import url("https://fonts.googleapis.com/css?  family=Lora:400,400i,700,700i");
                  </style>
                </defs>

                <rect
                  x="0"
                  y="0"
                  width="100%"
                  height="100%"
                  fill="url(#polka-dots)"
                ></rect>

                <text x="40%" y="60%" text-anchor="middle" style="font-size:30px">
                  Météo
                </text>
              </svg>
            </div>
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
            style="background-color: red; color: #fefee2; font-family: 'Zen Maru Gothic', sans-serif;"
            class="vertical-line"
          >
            <div class="patterns">
              <svg width="100%" height="100%">
                <defs>
                  <style>
                    @import url("https://fonts.googleapis.com/css?  family=Lora:400,400i,700,700i");
                  </style>
                </defs>

                <rect
                  x="0"
                  y="0"
                  width="100%"
                  height="100%"
                  fill="url(#polka-dots)"
                ></rect>

                <text x="50%" y="70%" text-anchor="middle">
                  Histoire
                </text>
              </svg>
            </div>
            <div class="wrapper" style="margin-bottom: 3px;">
              <div class="typing-demo1">
                Du paléolithique à nos jours,
              </div>
            </div>
            <div class="wrapper">
              <div class="typing-demo2">
                découvrez l’histoire de l’île de
                Bréhat, premier port de la baie de Saint Brieuc jusqu’à la fin
                du XVIIIème siècle, premier site classé de France en 1907.
              </div>
            </div>
            <br>
            <v-btn
              href="https://fr.wikipedia.org/wiki/%C3%8Ele-de-Br%C3%A9hat" target="_blank"
              elevation="2"
              style="float: right; background-color: #fefee2;"
              >En savoir plus</v-btn
            >
          </b-col>

          <b-col class="section1a"> </b-col>
        </b-row>

        <b-row>
          <b-col
            style="background-color: #fefee2; font-family: 'Poppins', sans-serif;"
            class="vertical-line"
          >
            <div class="patterns">
              <svg width="100%" height="100%">
                <defs>
                  <style>
                    @import url("https://fonts.googleapis.com/css?  family=Lora:400,400i,700,700i");
                  </style>
                </defs>

                <rect
                  x="0"
                  y="0"
                  width="100%"
                  height="100%"
                  fill="url(#polka-dots)"
                ></rect>

                <text x="50%" y="70%" text-anchor="middle" style="font-size:55px">
                  DERNIERS ARTICLES
                </text>
              </svg>
            </div>
            <br />
            <div style="display: flex; justify-content: space-around;">
              <Card img-src="https://i.picsum.photos/id/389/1024/480.jpg?hmac=LT_CS6C6B0Zp4Sixvz9cWxr-lRp0Fjc9moU3dUgIcpA"/>
              <Card />
              <Card />
            </div>
          </b-col>

          <b-col class="section1a"> </b-col>
        </b-row>

        <b-row>
          <b-col
            class="vertical-line"
            style="display: flex; justify-content: space-around; flex-direction: row; align-items: center; background-color: red;"
          >
            <Embed />

            <div
              style="display: flex; justify-content: space-around; flex-direction: column;"
            >
              <div style="display: flex; justify-content: space-around;">
                <b-img
                  src="https://www.oui.sncf/assets/media/2019-08/istock-fabrice-cabaud.jpg"
                  style="margin: 5px 5px 5px 5px; padding: 5px 5px 5px 5px; width: 250px; height: 188px;"
                ></b-img>
                <b-img
                  src="https://static.actu.fr/uploads/2020/07/img-9960.jpg"
                  style="margin: 5px 5px 5px 5px; padding: 5px 5px 5px 5px; width: 250px; height: 188px;"
                ></b-img>
              </div>

              <div style="display: flex; justify-content: space-around;">
                <b-img
                  src="https://www.bretagne.com/sites/default/files/post/Guide_pratique_ile_br%C3%A9hat_photo_Dominique_Douard.jpg"
                  style="margin: 5px 5px 5px 5px; padding: 5px 5px 5px 5px; width: 250px; height: 188px;"
                ></b-img>
                <b-img
                  src="https://cdn-elle.ladmedia.fr/var/plain_site/storage/images/loisirs/evasion/ile-de-brehat/65157923-3-fre-FR/Ile-de-Brehat-les-5-spots-immanquables-d-une-ile-enchanteresse.jpg"
                  style="margin: 5px 5px 5px 5px; padding: 5px 5px 5px 5px; width: 250px; height: 188px;"
                ></b-img>
              </div>
            </div>
          </b-col>
          <b-col class="section1a"></b-col>
        </b-row>
        <b-row>
          <b-col
            style="background-color: #fefee2; height: 250px"
            class="vertical-line"
          >
          </b-col>

          <b-col class="section1a"> </b-col>
        </b-row>

        <ScrollToTopBtn />
      </b-container>
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
@import url("https://fonts.googleapis.com/css2?family=Zen+Maru+Gothic:wght@300&display=swap");

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
  background-color: #fefee2;
  width: 100%;
  display: flex;
  flex-direction: column;
  align-items: center;
}

.vertical-line {
  border-right: 3px solid red;
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

.patterns {
  height: 10vh;
}

svg text {
  font-family: Lora;
  letter-spacing: 10px;
  stroke: #0f0303;
  font-size: 70px;
  font-weight: 700;
  stroke-width: 3;

  animation: textAnimate 5s infinite alternate;
}

@keyframes textAnimate {
  0% {
    stroke-dasharray: 0 50%;
    stroke-dashoffset: 20%;
    fill: hsl(189, 82%, 22%);
  }

  100% {
    stroke-dasharray: 50% 0;
    stroke-dashoffstet: -20%;
    fill: hsla(189, 68%, 75%, 0%);
  }
}

.wrapper {
  /*This part is important for centering*/
  display: flex;
  align-items: center;
  justify-content: center;
}

.typing-demo1 {
  width: 29ch;
  animation: typing 3s steps(29), blink 0.5s step-end infinite alternate;
  white-space: nowrap;
  overflow: hidden;
  border-right: 3px solid;
  font-family: monospace;
  font-size: 1em;
}

.typing-demo2 {
  width: 154ch;
  animation: typing 10s steps(154), blink 0.5s step-end infinite alternate;
  white-space: nowrap;
  overflow: hidden;
  border-right: 3px solid;
  font-family: monospace;
  font-size: 1em;
}

@keyframes typing {
  from {
    width: 0;
  }
}

@keyframes blink {
  50% {
    border-color: transparent;
  }
}
</style>
