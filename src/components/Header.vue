<template>
  <header class="text-gray-50 flex flex-row flex-nowrap items-center mx-8 my-8">
    <nav class="mr-32">
      <img src="https://cdn.discordapp.com/attachments/989919418870018068/989945907573309531/-1.png">
    </nav>
    <nav class="flex flex-row items-center text text-3xl">
      <div class="hover:underline">
        <router-link to="/" class="hover:underline">ГЛАВНАЯ</router-link>
      </div>
      <div class="line"></div>
      <router-link to="/price" class="hover:underline">ПРАЙС</router-link>
      <div class="line"></div>
      <router-link to="/design" class="hover:underline">ЗАКАЗАТЬ ДИЗАЙН</router-link>
    </nav>
  </header>
</template>
<style>
.line {
  background-color: white;
  height: 1px;
  width: 13px;
  margin-left: 58px;
  margin-right: 58px;
}
</style>