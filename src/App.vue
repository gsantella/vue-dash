<script setup>
import { RouterLink, RouterView } from "vue-router";
import HelloWorld from "@/components/HelloWorld.vue";
import NavBar from "@/components/NavBar.vue";
</script>

<template>

  <NavBar />

  <transition name="fade" mode="in-out">
       <RouterView style="margin-top: 70px" />
  </transition>


</template>

<style>

@import "@/assets/admin.css";

.fade-enter-active,
.fade-leave-active {
  transition: opacity 0.5s ease;
}

.fade-enter-from,
.fade-leave-active {
  opacity: 0.25;
}

</style>
