<template>
  <div>
    <!-- preloader start -->
    <div class="preloader">
      <div class="spinner"></div>
    </div>
    <!-- preloader end -->

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
                <li class="nav-item"><a href="#" class="nav-link">Work</a></li>
                <li class="nav-item"><a href="#" class="nav-link">About</a></li>
                <li class="nav-item"><a href="#" class="nav-link">Blog</a></li>
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

    <div class="main-container-outer">
      <!--=====================I ntro Start=====================-->
      <div
        class="intro-container parallax"
        data-parallax-speed="5"
        style="background-image:url(~assets/images/banner1.jpg);"
      >
        <div class="container">
          <div class="row">
            <div class="col-lg-9 col-md-11">
              <h6 class="subtitle">Welcome to MinShock Labs!</h6>
              <h1>
                We&apos;re Award Winning
                <span><i>Creative Digital Agency</i></span> that create
                <i>Brands</i>.
              </h1>
            </div>
          </div>
        </div>
      </div>
    </div>
    <!-- =====================  Intro End  ===================== -->

    <!-- =====================  Recent Project Start  ===================== -->
    <div class="project-container">
      <div class="container">
        <div class="row mar-40">
          <div class="col-md-12">
            <hgroup>
              <h6 class="subtitle">Recent Work</h6>
              <h5>Some amazing work of us</h5>
            </hgroup>
            <ul class="work-category">
              <li><a href="#" data-filter="" class="active">All</a></li>
              <li><a href="#" data-filter="one" class="">Website</a></li>
              <li><a href="#" data-filter="two" class="">Branding</a></li>
              <li><a href="#" data-filter="three" class="">Print</a></li>
            </ul>
            <div id="masonry" class="grid">
              <div class="grid-sizer"></div>
              <div class="gutter-sizer"></div>
              <ul class="my-work">
                <li data-filter="one" class="grid-item">
                  <div class="work-box">
                    <a href="#"
                      ><img src="~assets/images/project1.jpg" alt=""
                    /></a>
                  </div>
                  <div class="work-heading">
                    <a href="#">
                      <h6>Project Name</h6>
                      <p>Website</p>
                    </a>
                  </div>
                </li>
                <li data-filter="two" class="grid-item">
                  <div class="work-box">
                    <a href="#"
                      ><img src="~assets/images/project2.jpg" alt=""
                    /></a>
                  </div>
                  <div class="work-heading">
                    <a href="#">
                      <h6>Project Name</h6>
                      <p>Branding</p>
                    </a>
                  </div>
                </li>
                <li data-filter="three" class="grid-item">
                  <div class="work-box">
                    <a href="#"
                      ><img src="~assets/images/project3.jpg" alt=""
                    /></a>
                  </div>
                  <div class="work-heading">
                    <a href="#">
                      <h6>Project Name</h6>
                      <p>Print</p>
                    </a>
                  </div>
                </li>
                <li data-filter="two" class="grid-item">
                  <div class="work-box">
                    <a href="#"
                      ><img src="~assets/images/project4.jpg" alt=""
                    /></a>
                  </div>
                  <div class="work-heading">
                    <a href="#">
                      <h6>Project Name</h6>
                      <p>Branding</p>
                    </a>
                  </div>
                </li>
                <li data-filter="one" class="grid-item">
                  <div class="work-box">
                    <a href="#"
                      ><img src="~assets/images/project5.jpg" alt=""
                    /></a>
                  </div>
                  <div class="work-heading">
                    <a href="#">
                      <h6>Project Name</h6>
                      <p>Website</p>
                    </a>
                  </div>
                </li>
                <li data-filter="two" class="grid-item">
                  <div class="work-box">
                    <a href="#"
                      ><img src="~assets/images/project6.jpg" alt=""
                    /></a>
                  </div>
                  <div class="work-heading">
                    <a href="#">
                      <h6>Project Name</h6>
                      <p>Branding</p>
                    </a>
                  </div>
                </li>
                <li data-filter="three" class="grid-item">
                  <div class="work-box">
                    <a href="#"
                      ><img src="~assets/images/project7.jpg" alt=""
                    /></a>
                  </div>
                  <div class="work-heading">
                    <a href="#">
                      <h6>Project Name</h6>
                      <p>Print</p>
                    </a>
                  </div>
                </li>
              </ul>
            </div>
          </div>
        </div>
        <div class="row">
          <div class="col-md-6 offset-sm-3">
            <a href="#" class="btn btn-primary btn-block">View More Work</a>
          </div>
        </div>
      </div>
    </div>
    <!-- =====================  Recent Project End  ===================== -->

    <!-- =====================  Stats Start  ===================== -->
    <div class="stat-container grey-bg">
      <div class="container">
        <div class="row">
          <div class="col-md-12">
            <hgroup>
              <h6 class="subtitle">Awesome Stats!</h6>
              <h5>These number inspire us always.</h5>
            </hgroup>
            <ul class="stat-list">
              <li>
                <h3>
                  <span class="timer" data-to="859" data-speed="2000"></span>
                </h3>
                <h6>Satisfied Clients</h6>
              </li>
              <li>
                <h3>
                  <span class="timer" data-to="3622" data-speed="2000"></span>
                </h3>
                <h6>Completed Projects</h6>
              </li>
              <li>
                <h3>
                  <span class="timer" data-to="23" data-speed="2000"></span>
                </h3>
                <h6>Countries Served</h6>
              </li>
            </ul>
          </div>
        </div>
      </div>
    </div>
    <!-- =====================  Stats End  ===================== -->

    <!-- =====================  Client Start  ===================== -->
    <div class="client-container">
      <div class="container">
        <div class="row">
          <div class="col-md-12">
            <hgroup>
              <h6 class="subtitle">Awesome Client!</h6>
              <h5>We works with some big brands.</h5>
            </hgroup>
            <ul class="client-list">
              <li>
                <div>
                  <img src="~assets/images/client-logo.png" alt="" />
                </div>
              </li>
              <li>
                <div>
                  <img src="~assets/images/client-logo2.png" alt="" />
                </div>
              </li>
              <li>
                <div>
                  <img src="~assets/images/client-logo3.png" alt="" />
                </div>
              </li>
              <li>
                <div>
                  <img src="~assets/images/client-logo.png" alt="" />
                </div>
              </li>
              <li>
                <div>
                  <img src="~assets/images/client-logo2.png" alt="" />
                </div>
              </li>
              <li>
                <div>
                  <img src="~assets/images/client-logo3.png" alt="" />
                </div>
              </li>
              <li>
                <div>
                  <img src="~assets/images/client-logo.png" alt="" />
                </div>
              </li>
              <li>
                <div>
                  <img src="~assets/images/client-logo2.png" alt="" />
                </div>
              </li>
              <li>
                <div>
                  <img src="~assets/images/client-logo3.png" alt="" />
                </div>
              </li>
              <li>
                <div>
                  <img src="~assets/images/client-logo.png" alt="" />
                </div>
              </li>
            </ul>
          </div>
        </div>
      </div>
    </div>
    <!-- =====================  Client End  ===================== -->

    <!--  Bottom Start -->
    <div class="bottom-container">
      <h3>Ready to Start your Project?</h3>
      <a href="#" class="btn btn-secondary">Let&apos;s Start</a>
    </div>
    <!--  Bottom End -->

    <!--  Footer Start -->
    <footer>
      <ul class="social-links">
        <li><a href="#" target="_blank">Facebook</a></li>
        <li><a href="#" target="_blank">Twitter</a></li>
        <li><a href="#" target="_blank">Google+</a></li>
        <li><a href="#" target="_blank">Dribbble</a></li>
      </ul>
      <span class="copyright">&#xA9; Copyright. All rights reserved.</span>
    </footer>
    <!-- Footer End  -->

    <!-- Go top arrow -->
    <a href="#!" class="go-top"><i class="ti-arrow-up"></i></a>
  </div>
</template>

<script></script>

<style></style>
