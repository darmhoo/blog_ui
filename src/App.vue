<template>
  <div>
    <custom-header></custom-header>
    <router-view />
  </div>
</template>
<script lang="ts">
import { defineComponent } from "vue";
import Header from "@/components/Header.vue";
// @ is an alias to /src

export default defineComponent({
  name: "App",
  components: {
    CustomHeader: Header
  }
});
</script>

<style lang="scss"></style>
