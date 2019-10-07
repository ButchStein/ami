<template>
  <header class="header">
    <a href="#" class="header__logo"></a>
    <div class="header__text">
      <div class="header__adress DB15">Аминьевское шоссе, вл.15</div>
      <img class="header__clock" src="../assets/img/svg/clock.svg" />
      <a href="#" class="header__link DB15">
        10:00
        <span class="header__time"></span>
        <span class="header__time_dark"></span>
        22:00
      </a>
    </div>
  </header>
</template>
<script>
export default {};
</script>
<style lang="scss" scoped>
.header {
  width: 1200px;
  height: 100%;
  background-color: #0e8946;
  display: flex;
  flex-direction: row;
  justify-content: flex-end;
  align-items: center;
}
.header__logo {
  display: block;
  background-image: url(../assets/img/svg/logo-white.svg);
  width: 200px;
  height: 24.44px;
  margin: 30px 66px;
}

.header__text {
  display: flex;
  flex-wrap: nowrap;
  justify-content: space-between;
  margin-right: 179px;
}

.header__adress {
  text-transform: uppercase;
  color: #ffffff;
}

.header__clock {
  padding: 0 10px;
}

.header__link {
  display: flex;
  align-items: center;
  color: #ffffff;
  text-decoration: none;
  border-bottom: 1px dashed #ffffff;
}

.header__time {
  width: 9px;
  height: 2px;
  background-image: url(../assets/img/svg/h-line.svg);
  margin-left: 5px;
}

.header__time_dark {
  width: 11px;
  height: 2px;
  background-image: url(../assets/img/svg/h-line-d.svg);
  margin-right: 5px;
}
</style>