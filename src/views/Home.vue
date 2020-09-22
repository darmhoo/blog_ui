<template>
  <div id="page">
    <div id="content"></div>
    <div>
      <side-bar></side-bar>
    </div>
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import SideBar from "@/components/SideBar.vue";
// @ is an alias to /src

export default defineComponent({
  name: "Home",
  components: {
    SideBar
  }
});
</script>
