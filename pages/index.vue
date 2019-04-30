<template>
  <section>
    <h1>Hello</h1>
    <br>
    {{first}}
    <br>
    <br>
    <b-button @click="clickMe">Click Me</b-button>
  </section>
</template>

<script>
const something = ["Yay", "cool"];

export default {
  data() {
    return {
      first: something
    };
  },
  methods: {
    clickMe() {
      this.$notification.open("Clicked!");
    }
  }
};
</script>

<style scoped>
</style>
