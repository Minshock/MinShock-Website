<template>
  <div>
    <minheader />

    <minhero :background-url="require('~/assets/images/home-banner2.jpg')" />

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
import minheader from '~/components/MinHeader'
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

<style></style>
