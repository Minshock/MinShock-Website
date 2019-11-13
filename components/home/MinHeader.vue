<template>
  <!-- header start -->
  <header fixed="top">
    <div class="container">
      <div class="header-bar">
        <b-navbar toggleable="md">
          <b-navbar-brand href="#">
            <img
              src="~assets/images/logo.svg"
              width="30"
              height="30"
              class="d-inline-block align-top"
              alt="MinShock Labs"
            />
            MinShock
          </b-navbar-brand>

          <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

          <b-collapse id="nav-collapse" is-nav>
            <b-navbar-nav class="ml-auto">
              <b-nav-item href="#">Home</b-nav-item>
              <b-nav-item href="#">Work</b-nav-item>
              <b-nav-item href="#">About</b-nav-item>
              <b-nav-item href="#">Blog</b-nav-item>
              <b-nav-item href="#">Contact</b-nav-item>
            </b-navbar-nav>
          </b-collapse>
        </b-navbar>
      </div>
    </div>
  </header>
  <!-- header end -->
</template>

<style scoped>
/* header {
  background: transparent;
  width: 100%;
  position: fixed;
  top: 0px;
  left: 0;
  top: 0;
  color: inherit;
  -webkit-backface-visibility: hidden;
  backface-visibility: hidden;
  z-index: 9999;
  font-size: 14px;
  color: #686868;
  transition: all 0.1s ease-in;
  border-bottom: solid 1px rgba(255, 255, 255, 0);
} */
</style>

<script>
export default {}
</script>
