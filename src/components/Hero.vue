<template>
  <div class="hero">
    <div class="hero__left">
      <h2 class="hero__title">Compose your smoothie!</h2>
      <p class="hero__description">
        Using oranges as the basis for your breakfast smoothie takes the idea of fresh-squeezed
        orange juice to a whole new place. You can create creamy smoothies with banana, pineaple
        juice, mango, avocado and coconut milk.
      </p>
      <button class="hero__button">Create your smoothie</button>
    </div>
    <div class="hero__right">
      <img class="hero__bottle" src="../assets/images/smoothie-bottle.svg" alt="" />
    </div>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator';

@Component
export default class Navbar extends Vue {}
</script>

<style lang="scss" scoped>
.hero {
  max-width: 1200px;
  margin: 60px auto 0;
  display: flex;
  padding: 24px;
  justify-content: space-between;

  &__left {
    max-width: 550px;
  }
  &__title {
    font-size: 56px;
    font-weight: 700;
  }
  &__bottle {
    width: 150px;
  }
  &__button {
    background-color: black;
    padding: 16px 24px;
    color: #e8eddf;
    border: none;
    outline: none;
    border-radius: 16px;
    font-weight: 700;
    font-size: 14px;
  }
  &__account {
    display: flex;
    align-items: center;
    gap: 16px;
    img {
      width: 35px;
      height: 35px;
    }
  }
}
</style>
