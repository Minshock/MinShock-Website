<template>
  <!-- header start -->
  <header>
    <div class="container">
      <div class="header-bar">
        <nav class="navbar navbar-light navbar-expand-md">
          <div class="logo">
            <a class="navbar-brand" href="#">
              <img
                src="~assets/images/logo.svg"
                width="30"
                height="30"
                class="d-inline-block align-top"
                alt="MinShock Labs"
              />
              MinShock
            </a>
          </div>
          <button
            type="button"
            class="navbar-toggler collapsed"
            data-toggle="collapse"
            data-target="#navbar"
            aria-expanded="false"
            aria-controls="navbar"
          >
            <span class="sr-only">Toggle navigation</span>&#x2630;
          </button>
          <div id="navbar" class="navbar-collapse collapse">
            <ul class="nav navbar-nav ml-auto">
              <li class="active nav-item">
                <a href="#" class="nav-link">Home</a>
              </li>
              <li class="nav-item">
                <a href="#" class="nav-link">Work</a>
              </li>
              <li class="nav-item">
                <a href="#" class="nav-link">About</a>
              </li>
              <li class="nav-item">
                <a href="#" class="nav-link">Blog</a>
              </li>
              <li class="nav-item">
                <a href="#" class="nav-link">Contact</a>
              </li>
            </ul>
          </div>
          <!--/.nav-collapse -->
        </nav>
      </div>
    </div>
  </header>
  <!-- header end -->
</template>

<style scoped>
header {
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
}
</style>

<script>
export default {}
</script>
