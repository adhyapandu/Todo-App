<template>
  <div id="app">
    <CompletedTodos></CompletedTodos>
    <GetTodo></GetTodo>
    <CurrentTodos></CurrentTodos>
  </div>
</template>

<script>
import GetTodo from './components/getTodo.vue'
import CurrentTodos from './components/currentTodo.vue'
import CompletedTodos from './components/completedTodo.vue'

export default {
  name: 'App',
  components: {
    GetTodo,
    CurrentTodos,
    CompletedTodos
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
