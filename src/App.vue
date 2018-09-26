<template>
  <div>
    <header class="header">
      <div class="header__logo-box">
        <img class="header__logo" src="./assets/img/logo-white.png" alt="Logo">
    </div>
        <div class="header__text-box">
          <h1 class="heading-primary">
            <span class="heading-primary--main">Outdoors</span>
            <span class="heading-primary--sub">is where life happens</span>
          </h1>
          <a href="#" class="btn btn--white btn--animated">Discover our tours</a>
        </div>
    </header>
    <!-- <grid-test /> -->
  </div>
</template>

<script>
import GridTest from './components/SimpleGrid';
export default {
  name: 'app',
  components: {
    GridTest
  }
};
</script>

<style lang="scss">
</style>
