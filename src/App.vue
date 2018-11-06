<template>
  <div id="app" class="draggable flex min-h-screen font-sans">
    <!-- <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </div> -->

    <sidebar></sidebar>

    <router-view/>
  </div>
</template>

<script>
import Sidebar from './components/Sidebar.vue'

export default {
  components: {
    Sidebar,
  }
  
}
</script>


<style src="./assets/css/main.css"></style>
