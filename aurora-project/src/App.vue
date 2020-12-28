<template>
  <div id="app">
    <!-- <router-link to="/">Home</router-link> -->
    <router-view />
  </div>
</template>

<style lang="scss">
@import url("https://fonts.googleapis.com/css2?family=Lato:wght@300;400;700&display=swap");
$fontfamily: "Lato";
$min-width: 320px;
$max-width: 1240px;

* {
  padding: 0px;
  margin: 0px;
  border: 0px;
}
*,
*:before,
*:after {
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  box-sizing: border-box;
}
:focus,
:active {
  outline: none;
}
a:focus,
a:active {
  outline: none;
}
aside,
nav,
footer,
header,
section {
  display: block;
}
html,
body {
  height: 100%;
  min-width: $min-width;
}
body {
  line-height: 1;
  font-size: 14px;
  font-family: $fontfamily;
  -ms-text-size-adjust: 100%;
  -moz-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
}
input,
button,
textarea {
  font-family: $fontfamily;
}
input::-ms-clear {
  display: none;
}
button {
  cursor: pointer;
}
button::-moz-focus-inner {
  padding: 0;
  border: 0;
}
a,
a:visited {
  text-decoration: none;
}
a:hover {
  text-decoration: none;
}
ul li {
  list-style: none;
}
img {
  vertical-align: top;
}
h1,
h2,
h3,
h4,
h5,
h6 {
  font-weight: inherit;
  font-size: inherit;
}
.d-flex {
  display: flex;
}
.justify-content-center {
  justify-content: center;
}
.align-items-center {
  align-items: center;
}
.flex-space-between {
  justify-content: space-between;
}
.pointer {
  cursor: pointer;
}
.bordered {
  border: 1px gray solid;
}
.wrapper {
}
.container {
  max-width: $max-width;
  margin-left: auto;
  margin-right: auto;
}
.header {
  &__body {
    padding-top: 30px;
  }
  &__body-search {
    border-bottom: 2px gray solid;
    width: 400px;
  }
  &__body-search-input input {
    margin-bottom: 10px;
  }
  &__top {
    height: 40px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    font-size: 13px;
    font-weight: 400;
    color: #000000;
  }
  &__top-links {
    padding-right: 20px;
  }
  &__column:nth-child(2) &__top-links {
    padding: 20px;
    border-left: 1px gray solid;
  }
  &__column:nth-child(2) &__top-links:nth-child(2) {
    padding: 20px;
    border-right: 1px gray solid;
  }
  &__top-links img {
    padding-right: 10px;
  }
  &__top-line {
    height: 1px;
    background-color: gray;
    width: 100vw;
    margin: 0;
    padding: 0;
  }
  &__column {
    flex-direction: row;
    height: 100%;
  }
  &__logo {
  }
}
</style>
