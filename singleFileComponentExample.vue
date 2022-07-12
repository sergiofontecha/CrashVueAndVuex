<template>
  <ul>
    <todo-item
      v-for="(todo, index) in todoList"
      :key="index"
      :todo="todo"
    ></todo-item>
  </ul>
</template>

<script>
export default {
  name: 'todo-list',
  props: ['todoList'],
  methods: {},
};
</script>

<style scoped>
ul {
  list-style-type: none;
}
</style>
