<template>
  <div id="app">
    <h1>TO DO LIST 📝</h1>
    <Todos v-bind:todos='todos'/>
  </div>
</template>

<script>
import Todos from './components/Todos';
export default {
  name: 'App',
  components: {
    Todos
  },
  data() {
    return {
      todos: [
        {
          id: 1,
          title: 'do dishes',
          completed: false
        },
        {
          id: 2,
          title: 'do laundry',
          completed: false
        },
        {
          id: 2,
          title: 'do work',
          completed: false
        }
      ]
    }
  }
}
</script>

<style>

</style>
