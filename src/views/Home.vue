<template>
  <div class="home">
    Home
    <Counter />
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
