<template>
    <div style="display: flex;flex-direction: column;">
        <HeaderVue/>
        <NavigationVue/>
        <div style="display: flex;">
          <MenuVue/>
          <MainVue/>
          <ArticleVue/>
        </div>
    </div>
</template>

<script setup>
import ArticleVue from "./Article.vue";
import HeaderVue from "./Header.vue";
import MainVue from "./Main.vue";
import MenuVue from "./Menu.vue";
import NavigationVue from "./Navigation.vue";
</script>

<style>

</style>