<template>
  <header>
    <h1>Task Traker</h1>
    <Button text="Add Task" color="green" />
  </header>
</template>
<script>
import Button from "./Button.vue";
export default {
  name: "HeaderOne",
  components: {
    Button,
  },
};
</script>
<style scoped>
header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-bottom: 20px;
}
</style>
