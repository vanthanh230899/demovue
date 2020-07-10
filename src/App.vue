<template>
  <div id="app">
    <div class="container">
      <h1>TODO LIST</h1>
      <AddTodo/>
      <FilterTodo/>
      <Todos/>
    </div>
  </div>
</template>

<script>
import Todos from './components/Todos.vue';
import AddTodo from './components/AddTodo.vue';
import FilterTodo from './components/FilterTodo.vue';

export default {
  name: 'App',
  components: {
    Todos,
    AddTodo,
    FilterTodo
  }
}
</script>

<style>
body{
  font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
  line-height: 1.6;
  background: #e8f7f0;
}
.container{
  max-width: 1100px;
  margin: auto;
  overflow: auto;
  padding: 0 20px;
}
</style>
