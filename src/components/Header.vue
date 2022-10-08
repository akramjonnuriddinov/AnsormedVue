<template>
  <header>
    <div class="container flex items-center justify-between px-5 py-6 mx-auto">
      <a class="mr-4 hover:opacity-80" href="#">
        <img src="../assets/img/logo.png" alt="">
      </a>
      <!-- NAVBAR.VUE -->
      <Navbar />
      <Button />
    </div>
  </header>
</template>

<script>
import Navbar from './Navbar'
import Button from './Button'

export default {
  name: 'App',
  components: {
    Navbar,
    Button
  }
}
</script>

<style>

</style>