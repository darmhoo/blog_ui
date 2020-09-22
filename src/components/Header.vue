<template>
  <div id="header" class="container">
    <div id="logo">
      <h1>
        <a href="#">My <span>Blog</span></a>
      </h1>
    </div>
    <div id="menu">
      <ul>
        <li>
          <router-link to="/" class="current_page_item">Home</router-link>
        </li>
        <li><router-link to="/about">About</router-link></li>
        <li><a href="#">Blog</a></li>
        <li><a href="#">Contact</a></li>
        <li><a href="#">Photos</a></li>
      </ul>
    </div>
    <div id="banner"></div>
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
  name: "Header"
});
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss"></style>
