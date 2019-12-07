<template>
  <!-- header start -->
  <header>
    <b-navbar v-scroll="handleScroll" toggleable="md" fixed="top">
      <div class="container">
        <b-navbar-brand href="/">
          <img
            src="~assets/images/logo.svg"
            width="30"
            height="30"
            class="d-inline-block align-top"
            alt="MinShock Labs"
          />
          MinShock Labs
        </b-navbar-brand>

        <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

        <b-collapse id="nav-collapse" is-nav>
          <b-navbar-nav class="ml-auto">
            <b-nav-item href="/">Home</b-nav-item>
            <b-nav-item href="/work">Work</b-nav-item>
            <b-nav-item href="/about">About</b-nav-item>
            <b-nav-item href="/contact">Contact</b-nav-item>
          </b-navbar-nav>
        </b-collapse>
      </div>
    </b-navbar>
  </header>
  <!-- header end -->
</template>

<style scoped></style>

<script>
export default {
  directives: {
    scroll: {
      inserted(element, binding) {
        const f = function(event) {
          if (binding.value(event, element)) {
            window.removeEventListener('scroll', f)
          }
        }
        window.addEventListener('scroll', f)
      }
    }
  },

  methods: {
    handleScroll(event, element) {
      if (window.scrollY > 20) {
        element.setAttribut(
          'style',
          'background: #fff; transform: translate3d(0, -10px 0)'
        )
      }
      return window.scrollY > 100
    }
  }
}
</script>
