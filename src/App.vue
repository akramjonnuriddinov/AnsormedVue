<template>
  <div>
    <Header />
    <Hero />
    <Service />
    <Contact />
    <Footer />
  </div>
</template>

<script>
import Header from './components/Header'
import Hero from './components/Hero'
import Service from './components/Service'
import Contact from './components/Contact'
import Footer from './components/Footer'

export default {
  name: 'App',
  components: {
    Header,
    Hero,
    Service,
    Contact,
    Footer
}
}
</script>

<style>

body {
  font-family: "Open Sans", "Arial", sans-serif;
  font-weight: 400;
}

*:focus {
  outline: 3px dashed red !important;
  outline-offset: 3px;
}
</style>
