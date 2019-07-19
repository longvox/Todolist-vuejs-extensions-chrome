<template>
  <p>Todolist
    <Todos />
  </p>
  
</template>

<script>
import Todos from '../components/todoList';
export default {
  data() {
    return {};
  },
  components: {
    Todos,
  }
};
</script>

<style lang="scss" scoped>
p {
  font-size: 20px;
}
</style>
