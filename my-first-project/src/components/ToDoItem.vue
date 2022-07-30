<template>
<div>
  <ul v-for="item in array">
    <li>{{ item }}</li>
  </ul>
  <button @click="helloWorld">click me to print hello world</button>
</div>

</template>

<script>
export default {
  data() {
    return {
      array: [1, 2, 3, 4],
    };
  },
methods: {
  helloWorld () {
    console.log('hello world');
  }
}





};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped></style>
