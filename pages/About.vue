<template>
  <section class="container">
    <div>
      <logo/>
      <h1 class="title">
        About
      </h1>
      <h2 class="subtitle">
        A <a href="https://github.com/nuxt/nuxt.js" target="_blank">Nuxt.js</a> + <a href="https://github.com/cypress-io/cypress" target="_blank">Cypress</a> starter project template <br> without the distraction of a complicated <br> development environment.
      </h2>
      <div class="links">
        <nuxt-link to="/" class="button--green home-link">Home page</nuxt-link>
        <nuxt-link to="about" class="button--grey about-link">About page</nuxt-link>
      </div>
    </div>
  </section>
</template>

<script>
import Logo from '~/components/Logo.vue';

export default {
  components: {
    Logo
  }
};
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
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
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
