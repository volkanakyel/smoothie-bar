<template>
  <div>
    <Navbar />
    <Hero />
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator';
import Navbar from '@/components/Navbar.vue';
import Hero from '@/components/Hero.vue';

@Component({
  components: {
    Navbar,
    Hero,
  },
})
export default class App extends Vue {}
</script>

<style></style>
