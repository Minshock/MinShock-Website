<template>
  <div>
    <!-- preloader start -->
    <div class="preloader">
      <div class="spinner"></div>
    </div>
    <!-- preloader end -->

    <minheader />

    <minhero :background-url="require('~/assets/images/banner1.jpg')" />

    <minrecent />

    <minstats />

    <minclients />

    <mincta />

    <minfooter />

    <!-- Go top arrow -->
    <a href="#!" class="go-top">
      <i class="ti-arrow-up"></i>
    </a>
  </div>
</template>

<script>
import minhero from '~/components/home/MinHero'
import minheader from '~/components/home/MinHeader'
import minrecent from '~/components/home/MinRecent'
import minstats from '~/components/home/MinStats'
import minclients from '~/components/home/MinClients'
import mincta from '~/components/home/MinCTA'
import minfooter from '~/components/home/MinFooter'

export default {
  components: {
    minhero,
    minheader,
    minrecent,
    minstats,
    minclients,
    mincta,
    minfooter
  }
}
</script>

<style>
body {
  font-size: 15px;
  line-height: 27px;
  font-weight: 400;
  /* font-family: 'Quicksand'; */
  color: #273849;
  background: #fff;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>
