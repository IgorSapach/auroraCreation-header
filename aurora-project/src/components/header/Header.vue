<template>
  <header>
    <div class="container">
      <header-top />
    </div>
    <hr class="header__top-line" />
    <div class="container">
      <header-body />
      <header-nav />
    </div>
  </header>
</template>
<script>
import HeaderNav from "./HeaderNav";
import HeaderBody from "./HeaderBody";
import HeaderTop from "./HeaderTop";
export default {
  components: {
    HeaderNav,
    HeaderBody,
    HeaderTop,
  },
};
</script>
