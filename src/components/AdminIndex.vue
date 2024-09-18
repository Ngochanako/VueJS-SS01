<template>
  <div>
    <HeaderVue style="display: flex; flex-direction: column;"/>
    <div style="display: flex;">
        <MenuVue/>
        <div>
            <div style="height: 500px; width: 400px; display: flex; justify-content: center;align-items: center;">Main</div>
            <FooterVue/>
        </div>
    </div>
  </div>
</template>

<script setup>
import FooterVue from "./Footer.vue";
import HeaderVue from "./Header.vue";
import MenuVue from "./Menu.vue";
</script>

<style>

</style>