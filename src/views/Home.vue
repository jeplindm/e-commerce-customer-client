<template>
  <section class="home">
    <LandingPage/>
  </section>
</template>

<script>
// @ is an alias to /src
import LandingPage from '@/components/LandingPage.vue'

export default {
  name: 'Home',
  components: {
    LandingPage
  }
}
</script>
