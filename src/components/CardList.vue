<script setup>
import Card from './Card.vue'

defineProps({
  items: Array
})
const onClickAdd = () => {
  alert('Добавить')
}
</script>

<template>
  <div class="p-10">
    <div class="grid grid-cols-2 gap-5">
      <Card
        v-for="item in items"
        :key="item.id"
        :title="item.title"
        :image-url="item.imageUrl"
        :price="item.price"
        :onClickAdd="onClickAdd"
      />
    </div>
  </div>
</template>
