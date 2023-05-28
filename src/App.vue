<template>
  <div>
    <Navbar />
    <Hero />
    <SmoothieCard />
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator';
import Navbar from '@/components/Navbar.vue';
import Hero from '@/components/Hero.vue';
import SmoothieCard from '@/components/SmoothieCard.vue';

@Component({
  components: {
    Navbar,
    Hero,
    SmoothieCard,
  },
})
export default class App extends Vue {}
</script>

<style></style>
