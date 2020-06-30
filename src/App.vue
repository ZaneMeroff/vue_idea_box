<template>
  <div id="app">
    <h1>{{ todos[0].title }}</h1>
  </div>
</template>

<script>

export default {
  name: 'App',
  components: {

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
