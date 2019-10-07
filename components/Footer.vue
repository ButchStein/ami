<template>
  <footer class="footer">
    <div class="form__wrap">
      <form class="footer__form">
        <div class="form-section">
          <div class="form-section__title H3B23">подпишитесь на рассылку</div>
          <div class="form-group">
            <label class="form-group__label form-group__label--required form-group__label-mod">
              <input
                type="email"
                name="org[email]"
                class="form-group__input"
                required
                placeholder="эл.почта"
              />
            </label>
          </div>
        </div>
        <div class="form-section">
          <label
            class="form-group__label form-group__label--checkbox form-group__label--required DM11"
          >
            <span class="form__checkbox">
              Согласен на
              <a href="/polzovatelskoe-soglashenie" target="_blank">
                обработку персональных
                <br />данных
              </a>
            </span>
            <input type="checkbox" name="agree" class="form-group__input" required />
          </label>
          <label class="form-group__label form-group__label--button">
            <button class="form__btn DB15" type="submit">подписаться</button>
          </label>
        </div>
      </form>
      <div class="footer__image">
        <img src="../assets/img/svg/footer_img.svg" />
      </div>
    </div>
    <div class="footer__body">
      <div class="footer__socials">
        <div class="footer__social">
          <a href="#" class="footer__link-vk"></a>
        </div>
        <div class="footer__social">
          <a href="#" class="footer__link-instagram"></a>
        </div>
        <div class="footer__social">
          <a href="#" class="footer__link-facebook"></a>
        </div>
      </div>
      <div class="footer__developer">
        <p class="footer__developer-text DM11">
          Сделано в
          <a href="#">Grom IT</a>
        </p>
        <img class="footer__developer-logo" src="../assets/img/svg/thunder.svg" alt="thunder" />
      </div>
    </div>
  </footer>
</template>
<script>
export default {};
</script>
<style lang="scss" scoped>
.footer {
  width: 100%;
  height: 402px;
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: flex-end;
  position: relative;
}

.form__wrap {
  width: 48%;
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: center;
  background-image: url(../assets/img/svg/footer_form_bg.svg);
  background-repeat: no-repeat;
  position: absolute;
  z-index: 1;
  flex-shrink: 0;
}

.footer__form {
  width: 259px;
  height: 242px;
  display: flex;
  flex-flow: column;
  justify-content: space-between;
  margin-left: 41px;
}

.form-section__title {
  text-transform: uppercase;
  color: #ffffff;
}

.form-group__label-mod {
  border-bottom: 2px solid #ffffff;
  margin-top: 17px;
}

.form-group__input {
  background: none;
  color: #ffffff;
  padding-left: 0;
}

.form-group__label + .form-group__label {
  margin-left: 0;
}

.form-group__input::placeholder {
  font-family: "Bebas Neue";
  font-size: 23px;
  line-height: 23px;
  font-weight: 700;
  color: rgba(255, 255, 255, 0.35);
  text-transform: uppercase;
}

.form-group__label--checkbox {
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  background-image: url(../assets/img/svg/checkbox.svg);
  background-repeat: no-repeat;
  color: #ffffff;
}

.form__checkbox {
  display: block;
  padding-left: 30px;
}

.form-group__checkbox {
  padding-left: 20px;
}

.footer__image {
  height: 100%;
}

.form__btn {
  width: 139px;
  height: 65px;
  background: none;
  text-transform: uppercase;
  color: #ffffff;
  border: 1px solid #ffffff;
  cursor: pointer;
}

.footer__body {
  width: 69%;
  height: 100%;
  background-color: #000000;
  position: absolute;
  right: 0;
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: center;
}

.footer__socials {
  display: flex;
  height: 160px;
  flex-direction: column;
  justify-content: space-between;
  margin-left: 260px;
}

.footer__social {
  width: 40px;
  height: 40px;
  background-color: rgba(255, 255, 255, 0.15);
  display: flex;
  justify-content: center;
  align-items: center;
}

.footer__link-vk {
  width: 16px;
  height: 10px;
  background-image: url(../assets/img/svg/vk.svg);
}

.footer__link-instagram {
  width: 16px;
  height: 16px;
  background-image: url(../assets/img/svg/instagram.svg);
}

.footer__link-facebook {
  width: 6px;
  height: 13px;
  background-image: url(../assets/img/svg/facebook.svg);
}

.footer__developer {
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  align-items: center;
}

.footer__developer-text {
  writing-mode: vertical-rl;
  color: rgba(255, 255, 255, 0.5);
  transform: rotate(180deg);
}

.footer__developer-logo {
  padding-top: 10px;
}
</style>