<template>
  <div>
    <div v-for='todo in todos' v-bind:key='todo.id'>
      <p>{{ todo.title }}</p>
    </div>
  </div>

</template>

<script>
  export default {
    name: 'Todos',
    props: ['todos']
  }
</script>

<style scoped>

</style>
