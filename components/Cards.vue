<template>
  <div class="cards">
    <h2>{{ title }}</h2>
    <ul class="cards__list">
      <li v-for="(item, index) in cards" :key="item.id" class="cards">
        {{ index }} - {{ item.name }}
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  props: {
    title: {
      type: String,
      default: 'Default Title',
    },
  },
  data() {
    return {
      cards: [
        { id: 1, name: 'Jon', age: 5 },
        { id: 2, name: 'Jessica', age: 25 },
        { id: 3, name: 'Silvio', age: '39' },
        { id: 4, name: 'Jenny', age: 30 },
        { id: 5, name: 'Lara', age: 33 },
        { id: 6, name: 'Rebecca', age: 12 },
        { id: 7, name: 'Paul', age: 22 },
        { id: 8, name: 'Urs', age: 28 },
      ],
    }
  },
  computed: {
    filteredCards() {
      return this.cards
    },
  },
}
</script>

<style>
.cards__list {
  width: 96%;
  max-width: 900px;
  margin: 0 auto;
  background-color: gray;
}
</style>
