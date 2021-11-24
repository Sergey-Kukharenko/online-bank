<template>
  <the-navbar />
  <the-side-bar />
  <div class="container with-nav">
    <app-message/>
    <router-view/>
  </div>
</template>

<script>
import TheNavbar from "../components/TheNavbar";
import AppMessage from "../components/ui/AppMessage";
import TheSideBar from "../components/TheSideBar";

export default {
  name: "MainLayout",
  components: {TheSideBar, TheNavbar, AppMessage},
}
</script>

<style scoped>

</style>
