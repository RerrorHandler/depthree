<template>
  <div id="app">
    <div id="nav">
    </div>
    <router-view/>
  </div>
</template>

<style lang="scss">
* {
  font-family: "GOTHIC";
  outline: none;
}
footer {
  font-family: "PALA";
}
.bgmain {
  background-image: url("assets/bgmain.png");
  background-size: cover;
  background-repeat:no-repeat;
}
.bg-original {
  background-color: #333333;
} 
body {
  background-color: #333333;
}
@font-face {
  font-family: "GOTHIC";
  src: local("GOTHIC"),
   url(assets/fonts/GOTHIC.TTF) format("truetype");
}
@font-face {
  font-family: "PALA";
  src: local("PALA"),
   url(assets/fonts/PALA.TTF) format("truetype");
}
</style>
