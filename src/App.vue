<template>
  <div>
    <Web-header></Web-header>
    <router-view></router-view>
    <Web-footer></Web-footer>
  </div>
</template>

<script setup>
import WebFooter from "./components/footer/WebFooter.vue";
import WebHeader from "./components/header/WebHeader.vue";
</script>