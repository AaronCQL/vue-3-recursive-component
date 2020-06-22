<template>
  <div class="hello">
    {{ counter }}
    <hello-world v-if="counter < 10" :counter="counter + 1" />
  </div>
</template>

<script>
export default {
  props: {
    counter: Number,
  },
};
</script>
