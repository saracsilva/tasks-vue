<template>
  <div class="task">
    <h3>{{ task.text }}</h3>
    <p>{{ task.day }}</p>
  </div>
</template>
<script>
export default {
  name: "TaskItem",
  props: {
    task: Object,
  },
};
</script>
<style>
.task {
  background: #f4f4f4;
  margin: 5px;
  padding: 10px 20px;
  cursor: pointer;
}
.task.reminder {
  border-left: 5px solid green;
}
.task h3 {
  display: flex;
  align-items: center;
  justify-content: space-between;
}
</style>
