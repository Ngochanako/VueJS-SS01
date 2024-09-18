<script setup>
import ListCourseVue from "./components/ListCourse.vue";
import ColorBoxVue from "./components/ColorBox.vue";
import CardVue from "./components/Card.vue";
import CalculationVue from "./components/Calculation.vue";
import UserInfoVue from "./components/UserInfo.vue";
import FormartNameVue from "./components/FormatName.vue";
import AdminIndexVue from "./components/AdminIndex.vue";
import UserLayoutVue from "./components/UserLayout.vue";
import ManagerUserVue from "./components/ManagerUser.vue";
</script>
<template>
  <div>
    <ListCourseVue/>
    <ColorBoxVue/>
    <CardVue/>
    <CalculationVue/>
    <UserInfoVue/>
    <FormartNameVue/>
    <AdminIndexVue/>
    <UserLayoutVue/>
    <ManagerUserVue/>
  </div>
</template>

<style scoped>
/* header {
  line-height: 1.5;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
} */
</style>
