<template>
  <div class="menu">
    <img src="/Vector.png" class="menu__logo">
    <myMenu />
    <div class="menu__basket">
      <img src="/basket 1.png">
      <div class="basket__items-carts">1</div>
    </div>
  </div>
</template>

<script>
export default {
  name: "HeaderMenu",
}
</script>

<style scoped>
.menu {
  position: fixed;
  display: flex;
  left: 0;
  right: 0;
  background: black;
  align-items: center;
  justify-content: space-between;
  max-width: 1440px;
  height: 80px;
  color: white;
  z-index: 999;
  margin: auto;
}

.menu__logo {
  height: 35px;
  padding-left: 64px
}

.menu__basket {
  padding-right: 88px;
  position: relative
}

.basket__items-carts {
  display: flex;
  justify-content: center;
  align-items: center;
  position: absolute;
  right: 82px;
  bottom: 0;
  background: orange;
  border-radius: 300px;
  width: 16px;
  height: 16px;
  color: black;
  font-size: 12px;
  line-height: 24px;
}
</style>
