<template>
  <div class="main-container-outer clearfix">
    <div
      class="intro-container parallax"
      data-parallax-speed="5"
      :style="{ backgroundImage: `url(${backgroundUrl})` }"
    >
      <div class="container">
        <div class="row">
          <div class="col-lg-9 col-md-11">
            <h6 class="subtitle">Welcome to MinShock Labs!</h6>
            <h1>
              We&apos;re Award Winning
              <br />
              <span>
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
      default: '~/assets/images/banner1.jpg'
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
  background: #f6f6f6;
  opacity: 0.5;
}
</style>
