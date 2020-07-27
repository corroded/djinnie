<template>
  <div class="card-container">
    <header class="card-title">{{ title }}</header>
  </div>
</template>

<script lang="ts">
import Vue from 'vue';

export default Vue.extend({
  name: 'Card',
  props: {
    title: String,
  },
});
</script>

<style scoped lang="sass">
  .card-container
    padding: 3rem
    border: 1px solid #333
    margin: 1rem
</style>
