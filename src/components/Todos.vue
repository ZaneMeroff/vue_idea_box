<template>
  <div>
    <div v-for='todo in todos' v-bind:key='todo.id'>
      <li>{{ todo.title }}</li>
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
