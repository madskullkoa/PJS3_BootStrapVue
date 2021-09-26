<template id="">
  <div>
  <b-navbar toggleable="lg" type="dark">
    <b-navbar-brand href="#" class="ml-5">
      <img src=https://www.iledebrehat.fr/wp-content/uploads/2021/01/logo-brehat-test7.png class="d-inline-block align-top" alt="Logo" style="width: 15rem; height: auto;">
    </b-navbar-brand>

    <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

    <b-collapse id="nav-collapse" is-nav>
      <b-navbar-nav>
        <b-nav-item href="#" class="nav-hover">Accueil</b-nav-item>
        <b-nav-item href="#" class="nav-hover">Municipalité</b-nav-item>
        <b-nav-item href="#" class="nav-hover">Services Municipaux</b-nav-item>
        <b-nav-item href="#" class="nav-hover">Activités et Découvertes</b-nav-item>
        <b-nav-item href="#" class="nav-hover">Contact</b-nav-item>
        <b-nav-item href="#" class="nav-hover">Facebook</b-nav-item>
      </b-navbar-nav>
    </b-collapse>

  </b-navbar>
</div>
</template>

<script type="text/javascript">
</script>

<style media="screen">
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
</style>
