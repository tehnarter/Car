<script setup></script>
<template>
  <footer class="footer">
    <div class="footer__row">
      <div class="footer__info">
        Tagline lorem ipsum dolor sit amet, consectetur adipiscing eiusmod
      </div>
      <div class="footer__private">
        © 2018 Company. Privacy Policy | Terms & Conditions
      </div>
    </div>
  </footer>
</template>
<style lang="scss" scoped>
.footer {
  padding: 23px 0px 18px 0px;
  background: #02133c;
  // .footer__row

  &__row {
    display: flex;
    justify-content: space-around;
    @media (max-width: 767.98px) {
      flex-direction: column;
    }
  }

  // .footer__info

  &__info {
    font-family: "Roboto";
    font-style: normal;
    font-weight: 400;
    font-size: 12px;
    line-height: 18px;
    /* identical to box height, or 150% */

    letter-spacing: 0.15px;
    color: #959595;
  }

  // .footer__private

  &__private {
    font-family: "Roboto";
    font-style: normal;
    font-weight: 400;
    font-size: 12px;
    line-height: 18px;
    color: #959595;
    /* identical to box height, or 150% */

    letter-spacing: 0.15px;
    color: #959595;
  }
}
</style>
