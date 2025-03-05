<template>
  <HeaderView />
  <div class="container">
    <RouterView/>
  </div>
  <FooterView />
</template>

<script setup>
import FooterView from "./components/FooterView.vue";
import HeaderView from "./components/HeaderView.vue";
</script>

<style lang="scss" src="@/assets/style.scss"></style>
