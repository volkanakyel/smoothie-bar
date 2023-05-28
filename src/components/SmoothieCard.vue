<template>
  <div class="smoothie-card">
    <div class="smoothie-card__img">
      <img src="../assets/images/smoothie-bottle.svg" alt="">
    </div>
    <div class="smoothie-card__description">
      <p class="smoothie-card__title">Apple Smoothie</p>
      <p class="smoothie-card__quantity">250ml</p>
      <p class="smoothie-card__price">$79</p>
    </div>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator';

@Component
export default class SmoothieCard extends Vue {
}
</script>

<style lang="scss" scoped>
.smoothie-card {
  max-width: 250px;
  display: flex;
  gap: 24px;
  padding: 24px;
  box-shadow: 10px 5px 5px grey;
  border-radius: 24px;
  &__img {
    img {
    width: 40px;
    }
  }
}
</style>
