<template>
  <header>
    <header-top class="header__top" />
    <img src="/logo__aurora-box.png" />
    <div><input placeholder="Co chcesz kupić?" /></div>
    <div>
      <span><img src="/icon__basket.png" />Twój koszyk</span>
    </div>
    <header-nav />
  </header>
</template>
<script>
import HeaderNav from "./HeaderNav";
import HeaderTop from "./HeaderTop";
export default {
  components: {
    HeaderNav,
    HeaderTop,
  },
};
</script>
<style scoped>
.header__top {
  border-bottom: 1px gray solid;
}
</style>
