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
            <div class="composition">
              <img src="./assets/img/nat-1-large.jpg" alt="Photo 1" class="composition__photo composition__photo--p1">
              <img src="./assets/img/nat-2-large.jpg" alt="Photo 2" class="composition__photo composition__photo--p2">
              <img src="./assets/img/nat-3-large.jpg" alt="Photo 3" class="composition__photo composition__photo--p3">
            </div>
            </div>
          </div>
      </section>
      <section class="section-features">
        <div class="row">
          <div class="col-1-of-4">
            <div class="feature-box">
              <i class="feature-box__icon icon-basic-world"></i>
              <h3 class="heading-tertiary u-margin-bottom-small">Explore the world</h3>
              <p class="feature-box__text">
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Blanditiis sit nam unde, adipisci nobis id.
              </p>
            </div>
          </div>
          <div class="col-1-of-4">
            <div class="feature-box">
              <i class="feature-box__icon icon-basic-compass"></i>
              <h3 class="heading-tertiary u-margin-bottom-small">Meet nature</h3>
              <p class="feature-box__text">
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Blanditiis sit nam unde, adipisci nobis id.
              </p>
            </div>
          </div>
          <div class="col-1-of-4">
            <div class="feature-box">
              <i class="feature-box__icon icon-basic-map"></i>
              <h3 class="heading-tertiary u-margin-bottom-small">Find your way</h3>
              <p class="feature-box__text">
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Blanditiis sit nam unde, adipisci nobis id.
              </p>
            </div>
          </div>
          <div class="col-1-of-4">
            <div class="feature-box">
              <i class="feature-box__icon icon-basic-heart"></i>
              <h3 class="heading-tertiary u-margin-bottom-small">Live a healthier life</h3>
              <p class="feature-box__text">
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Blanditiis sit nam unde, adipisci nobis id.
              </p>
            </div>
          </div>
        </div>
      </section>
      <section class="section-tours">
        <div class="u-center-text u-margin-bottom-big">
          <h2 class="heading-secondary">
            Most popular tours
          </h2>
        </div>
        <div class="row">
          <div class="col-1-of-3">
            <div class="card">
              <div class="card__side card__side--front">
                <div class="card__picture card__picture--1">
                </div>
                <h4 class="card__heading">
                  <span class="card__heading-span card__heading-span--1">
                    The Sea Explorer
                  </span>
                </h4>
                <div class="card__details">
                  <ul>
                    <li>3 day tours</li>
                    <li>Up to 30 people</li>
                    <li>2 tour guides</li>
                    <li>Sleep in cozy hotels</li>
                    <li>Difficulty: Easy</li>
                  </ul>
                </div>
              </div>
              <div class="card__side card__side--back card__side--back-1">
                <div class="card__cta">
                  <div class="card__price-box">
                    <p class="card__price-only">Only</p>
                    <p class="card__price-value">$279</p>
                  </div>
                  <a href="#" class="btn btn--white">Book Now!</a>
                </div>
              </div>
            </div>
          </div>
          <div class="col-1-of-3">
            <div class="card">
              <div class="card__side card__side--front">
                <div class="card__picture card__picture--2">
                </div>
                <h4 class="card__heading">
                  <span class="card__heading-span card__heading-span--2">
                    The Forest Hiker
                  </span>
                </h4>
                <div class="card__details">
                  <ul>
                    <li>7 day tours</li>
                    <li>Up to 40 people</li>
                    <li>6 tour guides</li>
                    <li>Sleep in provided tents</li>
                    <li>Difficulty: Medium</li>
                  </ul>
                </div>
              </div>
              <div class="card__side card__side--back card__side--back-2">
                <div class="card__cta">
                  <div class="card__price-box">
                    <p class="card__price-only">Only</p>
                    <p class="card__price-value">$497</p>
                  </div>
                  <a href="#" class="btn btn--white">Book Now!</a>
                </div>
              </div>
            </div>
          </div>
          <div class="col-1-of-3">
            <div class="card">
              <div class="card__side card__side--front">
                <div class="card__picture card__picture--3">
                </div>
                <h4 class="card__heading">
                  <span class="card__heading-span card__heading-span--3">
                    The Snow Adventurer
                  </span>
                </h4>
                <div class="card__details">
                  <ul>
                    <li>5 day tours</li>
                    <li>Up to 15 people</li>
                    <li>3 tour guides</li>
                    <li>Sleep in cozy hotels</li>
                    <li>Difficulty: Hard</li>
                  </ul>
                </div>
              </div>
              <div class="card__side card__side--back card__side--back-3">
                <div class="card__cta">
                  <div class="card__price-box">
                    <p class="card__price-only">Only</p>
                    <p class="card__price-value">$897</p>
                  </div>
                  <a href="#" class="btn btn--white">Book Now!</a>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="u-center-text u-margin-top-huge">
          <a href="#" class="btn btn--green">Discover all tours</a>
        </div>
      </section>
      <section class="section-stories">
        <div class="bg-video">
          <video class="bg-video__content" autoplay muted loop>
            <source src="./assets/img/video.mp4" type="video/mp4">
            <source src="./assets/img/video.webm" type="video/webm">
            Your browser is no supported!
          </video>
        </div>
        <div class="u-center-text u-margin-bottom-big">
          <h2 class="heading-secondary">
            We make people genuinely happy
          </h2>
        </div>
        <div class="row">
          <div class="story">
            <figure class="story__shape">
              <img class="story__img" src="./assets/img/nat-8.jpg" alt="Person on tour">
              <figcaption class="story__caption">
                Mary Smith
              </figcaption>
            </figure>
            <div class="story__text">
              <h3 class="heading-tertiary u-margin-bottom-small">I had the best week ever with my family</h3>
              <p>
                Lorem, ipsum dolor sit amet consectetur adipisicing elit. Corrupti id, reiciendis sapiente quam animi similique, quod commodi expedita, reprehenderit aliquid dolorum eveniet molestiae ipsam. Quia, distinctio? Ut enim eum ad.
              </p>
            </div>
          </div>
        </div>
        <div class="row">
          <div class="story">
            <figure class="story__shape">
              <img class="story__img" src="./assets/img/nat-9.jpg" alt="Person on tour">
              <figcaption class="story__caption">
                Jack Wilson
              </figcaption>
            </figure>
            <div class="story__text">
              <h3 class="heading-tertiary u-margin-bottom-small">WOW! My life is completely different now</h3>
              <p>
                Lorem, ipsum dolor sit amet consectetur adipisicing elit. Corrupti id, reiciendis sapiente quam animi similique, quod commodi expedita, reprehenderit aliquid dolorum eveniet molestiae ipsam. Quia, distinctio? Ut enim eum ad.
              </p>
            </div>
          </div>
        </div>
        <div class="u-center-text u-margin-top-huge">
          <a href="#" class="btn-text">Read all stories &rarr;</a>
        </div>
      </section>

      <section class="section-book">
        <div class="row">
          <div class="book">
            <div class="book__form">
              <form action="#">
                <div class="u-margin-bottom-medium">
                  <h2 class="heading-secondary">
                    Start booking now
                  </h2>
                </div>
                <div class="form__group">
                  <input id="name" class="form__input" type="text" placeholder="Full name" required>
                  <label for="name" class="form__label">Full name</label>
                </div>
                <div class="form__group">
                  <input id="email" class="form__input" type="email" placeholder="Email address" required>
                  <label for="email" class="form__label">Email address</label>
                </div>
                <div class="form__group u-margin-bottom-medium">
                  <div class="form__radio-group">
                    <input name="size" type="radio" class="form__radio-input" id="small" checked>
                    <label class="form__radio-label" for="small">
                      <span class="form__radio-button"></span>
                      Small tour group
                    </label>
                  </div>
                  <div class="form__radio-group">
                    <input name="size" type="radio" class="form__radio-input" id="large">
                    <label class="form__radio-label" for="large">
                      <span class="form__radio-button"></span>
                      Large tour group
                    </label>
                  </div>
                </div>
                <div class="form-group">
                  <button class="btn btn--green">Next Step &rarr;</button>
                </div>
              </form>
            </div>
          </div>
        </div>
      </section>
    </main>
    <footer class="footer">
      <div class="footer__logo-box">
        <img src="./assets/img/logo-green-2x.png" alt="Full logo" class="footer__logo">
      </div>
        <div class="row">
          <div class="col-1-of-2">
            <div class="footer__navigation">
              <ul class="footer__list">
                <li class="footer__item">
                  <a href="#" class="footer__link">Company</a>
                </li>
                <li class="footer__item">
                  <a href="#" class="footer__link">Contact us</a>
                </li>
                <li class="footer__item">
                  <a href="#" class="footer__link">Career</a>
                </li>
                <li class="footer__item">
                  <a href="#" class="footer__link">Privacy</a>
                </li>
                <li class="footer__item">
                  <a href="#" class="footer__link">Terms</a>
                </li>
              </ul>
            </div>
          </div>
          <div class="col-1-of-2">
            <p class="footer__copyright">
              Build my <a href="#" class="footer__link">Jonas Schmedtmann</a> for this online course <a href="" class="footer__link">Advanced CSS and Sass</a>. Copyright &copy; by Jonas Schmedtmann. You are 100% to use this webpage for both personal and commercial use. but NOT to claim it as your own design. A credit to the original author, Jonas Schmedtmann, is of course highly appreciated!
            </p>
          </div>
        </div>
    </footer>
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
