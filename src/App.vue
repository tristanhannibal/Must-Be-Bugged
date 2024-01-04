<script setup>
import { RouterLink, RouterView } from 'vue-router'
// import HelloWorld from './components/HelloWorld.vue'
import MainPage from './components/MainPage.vue'
import DragonPopup from './components/DragonPopup.vue';

</script>

<template>
  <header>
    <MainPage></MainPage>
    <nav>
        <RouterLink to="/">About</RouterLink>
        <RouterLink to="/apply">Apply</RouterLink>
    </nav>
  </header>
  <RouterView />
  <DragonPopup></DragonPopup>
</template>

<style scoped>
 nav {
    text-align: left;
    margin-left: -1rem;
    font-size: 1rem;

    padding: 1rem 0;
    margin-top: 1rem;
  }

  nav {
  width: 100%;
  font-size: 12px;
  text-align: center;
  margin-top: 2rem;
}

nav a.router-link-exact-active {
  color: var(--text-colour-dark-2);
}

nav a.router-link-exact-active:hover {
  background-color: transparent;
}

nav a {
  display: inline-block;
  padding: 0 1rem;
  border-left: 1px solid var(--color-border);
  font-size: 2em;
}

nav a:first-of-type {
  border: 0;
}

header{
       align-self: center;
}
</style>
