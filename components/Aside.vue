<template>
  <div class="drawer__wrap">
    <div class="drawer">
      <a href="#" class="drawer__logo"></a>
      <a href="#" class="drawer__burger"></a>
      <div class="drawer__group">
        <a href="#" class="drawer__map"></a>
        <a href="#" class="drawer__howtoget"></a>
        <a href="#" class="drawer__search"></a>
      </div>
    </div>
  </div>
</template>
<script>
export default {};
</script>
<style lang="scss" scoped>
.drawer__wrap {
  background-color: #fff;
}
.drawer {
  width: 100%;
  height: 721px;
  background: #ffffff;
  display: flex;
  flex-flow: column;
  justify-content: space-between;
  align-items: center;
  align-content: center;
}

.drawer__group {
  display: flex;
  flex-flow: column;
}

.drawer__logo {
  display: block;
  width: 25px;
  height: 25px;
  background-image: url(..\assets\img\svg\logosmall.svg);
  background-repeat: no-repeat;
  margin-top: 30px;
}

.drawer__burger {
  display: block;
  width: 25px;
  height: 12px;
  background-image: url(..\assets\img\svg\burger.svg);
  background-repeat: no-repeat;
}

.drawer__map {
  display: block;
  width: 26px;
  height: 26px;
  background-image: url(..\assets\img\svg\trc_map.svg);
  background-repeat: no-repeat;
  margin-bottom: 17px;
}

.drawer__howtoget {
  display: block;
  width: 26px;
  height: 26px;
  background-image: url(..\assets\img\svg\howtoget.svg);
  background-repeat: no-repeat;
  margin-bottom: 17px;
}

.drawer__search {
  display: block;
  width: 26px;
  height: 27px;
  background-image: url(..\assets\img\svg\search.svg);
  background-repeat: no-repeat;
  margin-bottom: 16px;
}

.header__logo {
  display: block;
  background-image: url(..\assets\img\svg\logo-white.svg);
  width: 200px;
  height: 24.44px;
  margin: 30px 66px;
}
</style>