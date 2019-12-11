<template>
  <div class="main-container-outer clearfix">
    <div
      :style="{ backgroundImage: `url(${backgroundUrl})` }"
      class="intro-container parallax"
      data-parallax-speed="5"
    >
      <div class="container">
        <div class="row">
          <div class="col-lg-9 col-md-11">
            <h6 class="text-primary display-10">Welcome to MinShock Labs!</h6>
            <h1 class="display-3">
              We&apos;re Award Winning
              <br />
              <span class="text-primary">
                <i>Creative Digital Agency</i>
              </span>
              <br />that create <i>Brands</i>.
            </h1>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  props: {
    backgroundUrl: {
      type: String,
      default: '~/assets/images/banner2.jpg'
    }
  }
}
</script>

<style scoped>
.intro-container {
  background-position: 50% 0px;
  padding: 250px 0 190px;
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

.display-10 {
  font-size: 1.5rem;
  font-weight: 100;
  line-height: 1.2;
}
</style>
