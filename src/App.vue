<template>
  <div class="container">
      <ul class="navbar">
          <li class="prvi">
              <a href="portfolio.php" class="navLinks">portfolio</a>
          </li>
          <li class="drugi">
              <a href="home.php" class="navLinks">home</a>
          </li>
          <li class="logo">
              <img src="src/assets/OMLOGO.svg">
          </li>
          <li class="treci">
                  <a href="#" class="navLinks">hire</a>
          </li>
          <li class="cetvrti">
              <a href="#" class="navLinks">about</a>
          </li>
      </ul>
  </div>
</template>

<script>
export default {
  name: 'app',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<style lang="sass" scoped>
  @import 'app.sass'
</style>
