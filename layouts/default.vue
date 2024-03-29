<script lang="ts" setup>
import AppFooter from "~/components/AppFooter.vue";
import AppHeader from "~/components/AppHeader.vue";
</script>

<template>
  <AppHeader />
  <main>
    <slot />
  </main>
  <AppFooter />
</template>


<style>
html, body, #__nuxt, #__layout {
  font-family: Roboto, sans-serif;
  margin: 0px;
  height: 100% !important;
  width: 100% !important;
}

main {
  margin: 0px;
  height:100%;
  background-color: #0784b5;
  color: #fff
}

h1 {
  padding-top: 1rem;
  padding-bottom: 1rem;
  margin: 0px;
  text-align: center;
}

nav {
  background-color: #414c50;
  color: #fff;
  ul {
    list-style-type: none;
    margin: 0px;
    display: flex;
    flex-direction: row;
  }
  li {
    align-items: center;
  }
  a {
    padding: 0 1rem;
    font-size: x-large;
    color: #fff;
    display: flex;
    flex-direction: column;
    text-decoration: none;
  }
}

p{
  margin: 0px;
  text-align: center;
  font-size: large;
}

footer {
  width: 100%;
  bottom: 0px;
  margin: 0px;
  background-color: #414c50;
  color: #fff;
  text-align: center;
}
</style>