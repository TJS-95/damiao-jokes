<template>
  <section class="AppHeader">
    <b-navbar toggleable="lg" type="dark" variant="info">
      <b-navbar-brand href="/">Damaio Jokes</b-navbar-brand>
      <b-navbar-toggle target="jokesLinksBox"></b-navbar-toggle>
      <b-collapse id="jokesLinksBox" is-nav>
        <b-navbar-nav>
          <b-nav-item href="/">Home</b-nav-item>
          <b-nav-item href="/jokes">Jokes</b-nav-item>
          <b-nav-item href="/about">About</b-nav-item>
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>
  </section>
</template>

<script>
export default {
  name: 'AppHeader'
}
</script>

<style>

</style>