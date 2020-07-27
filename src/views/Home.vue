<template>
  <section class="home-page">
    <Card title="This is a card" />
    <Card title="Another card" />
    <Card title="The last card" />
  </section>
</template>

<script>
// @ is an alias to /src
import Card from '@/components/Card.vue';

export default {
  name: 'Home',
  components: {
    Card,
  },
};
</script>
