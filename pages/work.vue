<template>
  <div>
    <!-- ==================== Preloader start =================== -->
    <div class="preloader">
      <div class="spinner"></div>
    </div>
    <!-- ===================== preloader end ===================== -->

    <minheader />

    <div class="main-container-outer">
      <!-- ===================== Intro Start ===================== -->

      <div
        class="intro-container parallax"
        data-parallax-speed="5"
        style="background-image:url(_nuxt/assets/images/home-banner2.jpg);"
      >
        <div class="container">
          <div class="row">
            <div class="col-lg-9 col-md-11">
              <h6 class="text-primary display-6">Our Awesome Work!</h6>

              <h2 class="display-5">We focus on excellence with impact.</h2>

              <p>
                Lorem ipsum dolor sit amet, elit dolor, nisl congue nec
                consequat vitae phasellus. Ipsum ante varius conubia luctus,
                risus mi ullamcorper Duis laoreet est nec molestie volutpat.
              </p>
            </div>
          </div>
        </div>
      </div>

      <!-- =====================  Intro End  ===================== -->
      <!--=====================P roject Start=====================-->

      <div class="project-container mt-5">
        <div class="container">
          <div class="col-md-12">
            <div class="my-work row">
              <div class="grid-item col-md-6">
                <div class="work-box">
                  <a href="#">
                    <img
                      src="~assets/images/project3.png"
                      class="img-fluid"
                      alt="Responsive image"
                    />
                  </a>
                </div>

                <div class="work-heading">
                  <a href="#">
                    <h6>Project Name</h6>
                    <p>Website</p>
                  </a>
                </div>
              </div>

              <div class="grid-item col-md-6">
                <div class="work-box">
                  <a href="#">
                    <img
                      src="~assets/images/project2.png"
                      class="img-fluid"
                      alt="Responsive image"
                    />
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
            <div class="my-work row">
              <div class="grid-item col-md-6">
                <div class="work-box">
                  <a href="#">
                    <img
                      src="~assets/images/project2.png"
                      class="img-fluid"
                      alt="Responsive image"
                    />
                  </a>
                </div>

                <div class="work-heading">
                  <a href="#">
                    <h6>Project Name</h6>
                    <p>Website</p>
                  </a>
                </div>
              </div>

              <div class="grid-item col-md-6">
                <div class="work-box">
                  <a href="#">
                    <img
                      src="~assets/images/project3.png"
                      class="img-fluid"
                      alt="Responsive image"
                    />
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

      <!-- =====================  Project End  ===================== -->
    </div>

    <mincta />

    <minfooter />
    <!-- ===================== Go top arrow ==================== -->

    <a href="#!" class="go-top">
      <i class="ti-arrow-up"></i>
    </a>
  </div>
</template>

<script>
import minheader from '~/components/MinHeader'
import minfooter from '~/components/home/MinFooter'
import mincta from '~/components/home/MinCTA'

export default {
  components: {
    minheader,
    minfooter,
    mincta
  }
}
</script>

<style scoped>
.intro-container {
  background-position: 50% 0px;
  padding: 120px 0 90px;
  background-size: cover;
  position: relative;
}

.intro-container:before {
  content: '';
  position: absolute;
  left: 0;
  top: 0;
  right: 0;
  bottom: 0;
  background: #fff;
  opacity: 0.8;
}

.display-5 {
  font-size: 2.5rem;
  font-weight: 300;
  line-height: 1.2;
}

.display-6 {
  font-size: 1.5rem;
  font-weight: 200;
  line-height: 1.2;
}
</style>
