<template>
  <div class="home">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <ToDoItem/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'
import ToDoItem from '@/components/ToDoItem.vue';

export default {
  name: 'HomeView',
  components: {
    HelloWorld,
    ToDoItem
}
}
</script>
