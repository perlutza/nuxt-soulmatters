<template>
 <div>
<Header>
</Header>

       <nuxt-link to="/about">About</nuxt-link>
       <nuxt-link to="/contact">Contact</nuxt-link>

    <h1>Home page</h1>
     <nuxt-link to="/home">Acasa</nuxt-link>

  
  
  <section class="container">
    <div>
      <app-logo/>
      <h1 class="title">
        vuetifynuxt
      </h1>
      <h2 class="subtitle">
        Nuxt.js project
      </h2>
      <div class="links">
        <a
          href="https://nuxtjs.org/"
          target="_blank"
          class="button--green">Documentation</a>
        <a
          href="https://github.com/nuxt/nuxt.js"
          target="_blank"
          class="button--grey">GitHub</a>
      </div>
    </div>
  </section>
 </div>
</template>

<script>
import AppLogo from '~/components/AppLogo.vue'
import GridList from '~/components/GridList.vue'
import carousel from '~/components/carousel.vue'
import Header from '~/components/Header.vue'
import Footer from '~/components/Footer.vue'





export default {
  components: {
    AppLogo,
    GridList,
    carousel,
    Header,
    Footer
  }
}
</script>

<style>
.container {
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif; /* 1 */
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}



</style>
