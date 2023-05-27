<template>
  <div class="container">
    <div class="navbar">
      <p class="navbar__logo">Smoothie</p>
      <div class="navbar__nav-links">
        <ul>
          <li>About</li>
          <li>Smoothies</li>
          <li>Delivery</li>
        </ul>
      </div>
      <div class="navbar__account">
        <img src="../assets/images/icon-add.svg" alt="" />
        <img src="../assets/images/icon-user.svg" alt="" />
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator';

@Component
export default class Navbar extends Vue {}
</script>

<style lang="scss" scoped>
.navbar {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 0 24px;
  &__logo {
    font-size: 24px;
    font-weight: 700;
  }
  &__nav-links {
    ul {
      display: flex;
      list-style-type: none;
      gap: 16px;
    }
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
