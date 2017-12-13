<template>
  <div>
    <b-navbar toggleable fixed="top" variant="primary" type="dark">
      <b-navbar-brand href="#/">
        &bull;&bull; gamechoice &bull;&bull;
      </b-navbar-brand>
      <b-collapse is-nav id="nav_collapse">
        <b-navbar-nav class="ml-auto">
          <b-nav-item href="#/">
            gamechooser
          </b-nav-item>
          <b-nav-item href="#/api">
            api
          </b-nav-item>
          <b-nav-item href="#/about">
            about
          </b-nav-item>
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>
  </div>
</template>

<script>
  export default {
    name: 'Navbar',
  };
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  .navbar {
    z-index: 2000;
  }
</style>
