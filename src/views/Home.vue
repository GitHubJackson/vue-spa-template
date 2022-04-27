<template>
  <div class="home">
    Home
    <Counter />
    <span class="demo">demo</span>
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import Counter from '@/components/Counter.vue';

export default defineComponent({
  name: 'Home',
  components: {
    Counter,
  },
});
</script>

<style lang="less" scoped>
.home {
  padding: 16px;
}
</style>
