<template>
  <section>
    <h1>Hello</h1>
    <br>
    {{first}}
  </section>
</template>

<script>
const something = ["Yay", "cool"];

export default {
  data() {
    return {
      first: something
    };
  }
};
</script>

<style scoped>
</style>
