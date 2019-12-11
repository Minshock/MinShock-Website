<template>
  <!-- preloader start -->
  <div v-if="loading" class="preloader">
    <div class="spinner"></div>
  </div>
  <!-- preloader end -->
</template>

<style scoped>
.preloader {
  position: fixed;
  z-index: 99999;
  top: 0;
  left: 0;
  background: #fff;
  width: 100%;
  height: 100%;
  text-align: center;
}

.spinner {
  position: relative;
  top: 50%;
  -webkit-transform: translate(0, -50%);
  -moz-transform: translate(0, -50%);
  -ms-transform: translate(0, -50%);
  -o-transform: translate(0, -50%);
  transform: translate(0, -50%);
  display: inline-block;
  background-color: #000;
  width: 50px;
  height: 50px;
  -webkit-border-radius: 100%;
  -moz-border-radius: 100%;
  -ms-border-radius: 100%;
  -o-border-radius: 100%;
  border-radius: 100%;
  -webkit-animation: sk-scaleout 1s infinite ease-in-out;
  animation: sk-scaleout 1s infinite ease-in-out;
}
</style>

<script>
export default {
  data: () => ({
    loading: false
  }),
  methods: {
    start() {
      this.loading = true
    },
    finish() {
      this.loading = false
    }
  }
}
</script>
