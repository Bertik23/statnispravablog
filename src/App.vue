<template>
  <navbar :navSites="navSites"></navbar>
  <div id="nav">
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link>
  </div>
  <router-view />
</template>

<!-- <style lang="scss">
// #app {
//   font-family: Avenir, Helvetica, Arial, sans-serif;
//   -webkit-font-smoothing: antialiased;
//   -moz-osx-font-smoothing: grayscale;
//   text-align: center;
//   color: #2c3e50;
// }

// #nav {
//   padding: 30px;

//   a {
//     font-weight: bold;
//     color: #2c3e50;

//     &.router-link-exact-active {
//       color: #42b983;
//     }
//   }
// }
// </style> -->

<script lang="ts">
import { defineComponent } from 'vue'
import Navbar from './components/navbar.vue'
//import { Vue } from "vue-class-component";
//import { defineComponent } from '@vue/runtime-core';
//import Component from "vue-class-component";


export default defineComponent({
  components: {Navbar},
  data(){
    return {navSites: [
    {
        name: 'Home',
        url: '/'
    },
    {
        name: "About",
        url: "/about"
    }
    ]
  }}
})
</script>

