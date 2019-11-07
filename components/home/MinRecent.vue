<template>
  <!-- =====================  Recent Project Start  ===================== -->
  <div class="project-container">
    <div class="container">
      <div class="row mb-40">
        <div class="col-md-12">
          <hgroup>
            <h6 class="subtitle">Recent Work</h6>
            <h5>See some of our amazing work</h5>
          </hgroup>

          <div id="masonry" class="grid">
            <div class="grid-sizer"></div>
            <div class="gutter-sizer"></div>
            <div class="my-work row">
              <div data-filter="two" class="grid-item col-md-6">
                <div class="work-box">
                  <a href="#">
                    <img src="~assets/images/project2.jpg" alt />
                  </a>
                </div>
                <div class="work-heading">
                  <a href="#">
                    <h6>Project Name</h6>
                    <p>Branding</p>
                  </a>
                </div>
              </div>
              <div data-filter="one" class="grid-item col-md-6">
                <div class="work-box">
                  <a href="#">
                    <img src="~assets/images/project2.jpg" alt />
                  </a>
                </div>
                <div class="work-heading">
                  <a href="#">
                    <h6>Project Name</h6>
                    <p>Website</p>
                  </a>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="row">
        <div class="col-md-6 offset-sm-3">
          <a href="#" class="btn btn-outline-primary btn-block"
            >View More Work</a
          >
        </div>
      </div>
    </div>
  </div>
  <!-- =====================  Recent Project End  ===================== -->
</template>

<style scoped>
.project-container {
  width: 100%;
  display: inline-block;
  vertical-align: top;
  padding: 100px 0;
}

.mb-40 {
  margin-bottom: 40px !important;
}

/* .subtitle {
  color: #42b983;
} */

hgroup {
  margin-bottom: 50px;
}

.work-category {
  margin-bottom: 40px;
}

.work-box {
  float: left;
  width: 100%;
  position: relative;
  overflow: hidden;
}

.work-box a:before {
  content: '';
  position: absolute;
  left: 0;
  top: 0;
  right: 0;
  bottom: 0;
  background: rgba(0, 0, 0, 0.7);
  z-index: 9;
  opacity: 0;
  transition: all 0.1s ease-in;
  -moz-transition: all 0.1s ease-in;
  -o-transition: all 0.1s ease-in;
  -webkit-transition: all 0.1s ease-in;
  -ms-transition: all 0.1s ease-in;
}

.work-box img {
  width: 100%;
  position: relative;
  z-index: 1;
  -webkit-transition: all 1000ms cubic-bezier(0.19, 1, 0.22, 1) 0ms;
  -moz-transition: all 1000ms cubic-bezier(0.19, 1, 0.22, 1) 0ms;
  transition: all 1000ms cubic-bezier(0.19, 1, 0.22, 1) 0ms;
}

.work-box a:after {
  content: '\e61a';
  font-family: 'themify';
  position: absolute;
  top: 50%;
  opacity: 0;
  z-index: 10;
  left: 50%;
  width: 30px;
  height: 30px;
  line-height: 30px;
  margin: -15px 0 0 -15px;
  color: #fff;
  font-size: 24px;
  -webkit-transform: scale(0.4);
  -moz-transform: scale(0.4);
  -o-transform: scale(0.4);
  -ms-transform: scale(0.4);
  transform: scale(0.4);
  -webkit-transition: all 200ms linear;
  -moz-transition: all 200ms linear;
  -o-transition: all 200ms linear;
  -ms-transition: all 200ms linear;
  transition: all 200ms linear;
  -webkit-transition-delay: 0.3s;
  -o-transition-delay: 0.3s;
  -moz-transition-delay: 0.3s;
  transition-delay: 0.3s;
}

.work-heading {
  width: 100%;
  display: inline-block;
  vertical-align: top;
  padding: 15px;
  position: absolute;
  left: 0;
  right: 0;
  bottom: 0;
  z-index: 99;
}

.work-heading h6 {
  margin-bottom: 0;
  position: relative;
  color: #fff;
  transition: all 0.1s ease-in;
  -moz-transition: all 0.1s ease-in;
  -o-transition: all 0.1s ease-in;
  -webkit-transition: all 0.1s ease-in;
  -ms-transition: all 0.1s ease-in;
  top: 150px;
}

.work-heading p {
  color: #fff;
  margin-bottom: 0;
  position: relative;
  transition: all 0.3s ease-in;
  -moz-transition: all 0.3s ease-in;
  -o-transition: all 0.3s ease-in;
  -webkit-transition: all 0.3s ease-in;
  -ms-transition: all 0.3s ease-in;
  top: 150px;
}
</style>

<script>
export default {}
</script>
