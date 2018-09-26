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
    <main>
      <section class="section-about">
        <div class="u-center-text u-margin-bottom-big">
          <h2 class="heading-secondary">
            Exciting tours for adventurous people
          </h2>
        </div>
        <div class="row">
          <div class="col-1-of-2">
            <h3 class="heading-tertiary u-margin-bottom-small">You're goting to fall in love with nature</h3>
            <p class="paragraph">
              Lorem ipsum, dolor sit amet consectetur adipisicing elit. Ipsum rem eligendi commodi numquam aliquam dolor qui perferendis quae mollitia sit, praesentium necessitatibus cupiditate optio eos quis et repellendus. Blanditiis, ipsa.
            </p>
            <h3 class="heading-tertiary u-margin-bottom-small">Live adventyures like you never have before</h3>
            <p class="paragraph">
              Lorem ipsum dolor, sit amet consectetur adipisicing elit. Iure doloremque ad nulla rerum quam tempora labore voluptas est sed nesciunt. Doloremque quidem sint odio voluptates nisi blanditiis labore error quaerat.
            </p>
            <a href="#" class="btn-text">Learn more &rarr;</a>
          </div>
          <div class="col-1-of-2">
            Image Content
          </div>
        </div>
      </section>
    </main>
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
