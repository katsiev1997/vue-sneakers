<script setup>
import Card from './Card.vue'
const onClickAdd = () => {
    alert('Добавить')
}
</script>

<template>
  <div class="p-10">
    <h2 class="text-3xl font-bold mb-10">Все кроссовки</h2>
    <div class="grid grid-cols-4 gap-5">
      <Card
        title="Мужские кроссовки Nike Blazer Mid Suede"
        image-url="/sneakers/sneakers-1.jpg"
        :price="5000"
        :isFavorite="true"
        :onClickAdd="onClickAdd"
      />
    </div>
  </div>
</template>
