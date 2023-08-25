<script setup></script>
<template>
  <header class="header">
    <div class="header__container">
      <div class="header__row-logo">
        <a class="header__img-logo" href="">
          <img src="../assets/img/header/Vector.svg" alt="" />
        </a>
        <div class="header__hours">
          SERVICE HOURS <br />
          Mon - Sat: 7:00 am - 6:00 pm
        </div>
        <div class="header__phone">
          CALL US <br />
          (555) Car-Repair
        </div>
        <div class="header__button button-red">Make an Appointment</div>
      </div>
      <div class="header__nav">
        <div class="header__row-nav">
          <nav class="header__list">
            <ul class="header__nav-list">
              <li class="header__list-nav"><a href="">Services</a></li>
              <li class="header__list-nav"><a href="">Specials</a></li>
              <li class="header__list-nav"><a href="">Estimates</a></li>
              <li class="header__list-nav"><a href="">Reviews</a></li>
              <li class="header__list-nav"><a href="">Shop</a></li>
              <li class="header__list-nav"><a href="">About</a></li>
            </ul>
          </nav>
          <div class="header__shop">
            <div class="header__search">
              <img src="./assets/img/header/search.svg" alt="" />
            </div>
            <div class="header__shop-card">
              <img src="../assets/img/header/shopping_cart.svg" alt="" />
            </div>
          </div>
        </div>
      </div>
      <h1 class="header__title">Top notch service is our main auto motive</h1>
      <div class="header__subtitle button-red">Make an Appointment</div>
    </div>
  </header>
</template>
<style lang="scss" scoped>
.header {
  background: url(../assets/img/header/bg_image.jpg) center/cover no-repeat;
  min-height: 813px;

  &__logo {
  }

  // .header__row-logo

  &__row-logo {
    display: flex;
    align-items: center;
  }

  // .header__icon-logo

  &__img-logo {
    margin: 26px 0px;
    flex: 1 1 auto;
  }
  &__img-logo > img {
    vertical-align: middle;
  }

  // .header__img-logo

  &__img-logo::before {
    content: "";
    margin-right: 10px;
    background-image: url(../assets/img/main/sec__contact/logo.svg);
    display: inline-block;
    width: 40px;
    height: 41px;
    vertical-align: middle;
  }

  // .header__utility

  &__utility {
  }

  // .header__hours

  &__hours {
    position: relative;
    margin: 26px 30px 27px 0px;
    font-family: Roboto;
    font-size: 12px;
    font-weight: 700;
    line-height: 22px;
    letter-spacing: 0.15000000596046448px;
    text-align: left;
    color: #fff;
  }
  &__hours::before {
    content: "";
    position: absolute;
    top: 0px;
    left: -30px;
    background-image: url(../assets/img/header/access.svg);
    width: 24px;
    height: 24px;
    display: inline-block;
  }

  // .header__phone

  &__phone {
    position: relative;
    margin: 26px 32px 27px 0px;
    font-family: Roboto;
    font-size: 12px;
    font-weight: 500;
    line-height: 22px;
    letter-spacing: 0.15000000596046448px;
    text-align: left;
    color: #fff;
  }
  &__phone::before {
    content: "";
    position: absolute;
    top: 0px;
    left: -30px;
    background-image: url(../assets/img/header/phone.svg);
    width: 24px;
    height: 24px;
    display: inline-block;
  }

  // .header__button

  &__button {
    margin: 26px 0px 27px 0px;
    width: 211px;
    height: 40px;

    // &:hover {
    //   top: 30px;
    //   transition-duration: 5s;
    //   border-radius: 0px;
    //   opacity: 1;

    // top: 2px;
    // box-shadow: 0 2px 0px #d35e5e;
    // border-radius: 10px;
    // transform: translateX(30%);
    // animation-play-state: paused;
  }

  // .header__nav

  &__nav {
    margin: 0px 0px 126px 0px;
    padding: 10px 40px;
    background: #ffffff;
    height: 60px;
  }

  // .header__row-nav

  &__row-nav {
    display: flex;
    justify-content: space-between;
    height: 100%;
    align-items: center;
  }

  // .header__list

  &__list {
  }

  // .header__nav-list

  &__nav-list {
    display: flex;
    flex-wrap: wrap;
  }

  &__list-nav {
    position: relative;
    margin: 0px 0px 0px 37px;
    font-family: Roboto;
    font-size: 14px;
    font-weight: 700;
    line-height: 22px;
    letter-spacing: 0.15000000596046448px;
    text-align: center;
  }
  &__list-nav > a {
    color: #02133c;
  }
  &__list-nav:nth-child(2)::after {
    content: "";
    position: absolute;
    top: 3px;
    right: 20;
    background-image: url(../assets/img/header/expand_more.svg);
    display: inline-block;
    width: 15px;
    height: 10px;
  }
  &__list-nav:nth-child(5)::after {
    content: "";
    position: absolute;
    top: 3px;
    right: 20;
    background-image: url(../assets/img/header/expand_more.svg);
    display: inline-block;
    width: 15px;
    height: 10px;
  }

  // .header__shop

  &__shop {
    display: flex;
  }

  // .header__search

  &__search {
  }

  // .header__shop-card
  &__shop-card {
    position: relative;
    margin-left: 22px;
  }
  &__shop-card::before {
    content: "";
    position: absolute;
    top: -3px;
    right: -3px;
    background-color: #c40b0b;
    border-radius: 50%;
    display: inline-block;
    width: 12px;
    height: 12px;
  }
  &__shop-card::after {
    content: "2";
    position: absolute;
    color: #ffffff;
    top: -3px;
    right: -9px;

    display: inline-block;
    width: 16px;
    height: 16px;
  }
  // .header__title

  &__title {
    //styleName: /Default/56 • H1 Heading;
    margin: 0px 0px 48px 0px;
    max-width: 583px;
    font-family: Roboto;
    font-size: 56px;
    font-weight: 900;
    line-height: 56px;
    letter-spacing: 0px;
    text-align: left;
    color: #fff;
    transition-timing-function: ease-in;
    animation-name: title;
    animation-duration: 5s;
    animation-timing-function: ease-in;
    animation-iteration-count: 1;
    animation-direction: alternate;
    animation-delay: 0s;
  }
  @keyframes title {
    0% {
      opacity: 0;
    }
    100% {
      opacity: 1;
    }
  }
  // .header__subtitle

  &__subtitle {
    width: 211px;
    height: 48px;
  }
}
.button-red {
  //styleName: /Default/16 • Button ;
  position: relative;
  background-color: #e30b0b;
  padding: 9px 0px 9px 15px;
  border-radius: 5px;
  font-family: Roboto;
  font-size: 12px;
  font-weight: 700;
  line-height: 24px;
  color: #fff;
}
.button-red::after {
  content: "";
  position: absolute;
  top: 33.333%;
  right: 10px;
  background-image: url(../assets/img/header/arrow_forward.svg);
  display: inline-block;
  width: 10.67px;
  height: 10.67px;
}
</style>
