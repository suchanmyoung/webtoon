<template>
  <button type="button" class="btn btn-outline-success">Success</button>

  <router-link to="/">홈페이지</router-link>
  <router-link to="/list">리스트페이지</router-link>
  <router-view :Blog="Blog"></router-view>


</template>


<script>

import Blog from './assets/blog.js';

export default {
  name: 'App',
  data(){
    return {
      Blog : Blog,
    }
  },
  components: {
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
