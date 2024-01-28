<script setup>
import Header from './components/Header.vue'
import Drawer from './components/Drawer.vue'
import CardList from './components/CardList.vue'
</script>

<template>
  <Drawer />
  <div class="w-4/5 m-auto bg-white rounded-xl shadow-xl mt-14">
    <Header />
    <CardList />
  </div>
</template>

<style scoped></style>
