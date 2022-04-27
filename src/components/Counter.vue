<template>
  <div class="container">
    <a-button @click="increment">+</a-button>
    <div>{{ count }}</div>
    <a-button @click="decrement">-</a-button>
  </div>
</template>

<script>
import { ref } from 'vue';
export default {
  name: 'Counter',
  setup() {
    const count = ref(0);
    function increment() {
      ++count.value;
    }
    function decrement() {
      --count.value;
    }
    return { increment, decrement, count };
  },
};
</script>

<style lang="less" scoped>
.container {
  display: flex;
  align-items: center;
  gap: 16px;
  padding: 16px 0;
}
</style>
