<template>
  <div class="header__top">
    <div class="left-side header__top">
      <span><img src="/icon__phone.png" />293 939 098</span>
      <span><img src="/icon__mail.png" />kontakt@aurorabox.pl</span>
    </div>
    <div class="header__top">
      <div class="right-side">
        <span><img src="/icon__user.png" />Załóż konto</span>
      </div>
      <span><img src="/icon__lock.png" />Zaloguj się</span>
    </div>
  </div>
</template>

<style>
.header__top {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  color: #000000;
  font-family: Lato;
  font-size: 13px;
  font-weight: 400;
  font-style: normal;
  letter-spacing: normal;
  line-height: 16.68px;
  text-align: left;

  font-style: normal;
  letter-spacing: normal;
  line-height: normal;
}
.right-side {
  border-left: 1px gray solid;
  border-right: 1px gray solid;
}
</style>
