<template id="">
  <b-navbar toggleable="lg" type="dark" class="sticky" fixed="top" style="justify-content: space-around; width:100" >
    <b-container>
    <b-navbar-brand href="#">
      <img src=https://www.iledebrehat.fr/wp-content/uploads/2021/01/logo-brehat-test7.png class="d-inline-block align-top" alt="Logo" style="width: 15rem; height: auto;">
    </b-navbar-brand>

    <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

    <b-collapse id="nav-collapse" style="justify-content: space-around" is-nav>
      <b-navbar-nav style="margin-right: 3em">
        <b-nav-item href="#" class="nav-hover font">ACCUEIL</b-nav-item>
        <b-nav-item href="#" class="nav-hover font">MUNICIPALITÉ</b-nav-item>
        <b-nav-item href="#" class="nav-hover font">SERVICES MUNICIPAUX</b-nav-item>
        <b-nav-item href="#" class="nav-hover font">ACTIVITÉS ET DÉCOUVERTES</b-nav-item>
        <b-nav-item href="#" class="nav-hover font">CONTACT</b-nav-item>
        <b-nav-item href="#" class="nav-hover font">FACEBOOK</b-nav-item>
      </b-navbar-nav>
    </b-collapse>
  </b-container>
  </b-navbar>
</template>

<script type="text/javascript">
</script>

<script>
import { ref } from 'vue';
export default {
  props: {},
  setup() {
    },
};
</script>

<style media="screen">

@import url('https://fonts.googleapis.com/css2?family=Bebas+Neue&family=Poppins:wght@300;600&display=swap');

  li {
    margin-bottom: 10px;
}

.nav-hover {
    display: inline-block;
    color: white;
    text-decoration: none;
}

.nav-hover::after {
    content: '';
    display: block;
    width: 0;
    height: 2px;
    background: white;
    transition: width .3s;
}

.nav-hover:hover::after {
    width: 100%;
    transition: width .3s;
}

.font {
  font-family: 'Bebas Neue', cursive;
  font-family: 'Poppins', sans-serif;
  margin-top: 1rem;
  margin-right: 1em;
}

.container, .container-fluid, .container-sm, .container-md, .container-lg, .container-xl {
    justify-content: space-around
}

.change_color {
  background-color: red;
}
</style>
