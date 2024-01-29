<template>
  <div>
    <div>
      <NavBar />
    </div>
    <div>
      <Main />
    </div>
    <div>
      <AboutMe />
    </div>
  </div>
</template>
<script lang="ts">
import NavBar from '../components/Navbar.vue'
import Main from '../components/Main.vue'
import AboutMe from '../components/AboutMe.vue'

export default {
  name: 'MainPage',
  components: {
    NavBar,
    AboutMe,
    Main
  }
}
</script>
<style></style>
