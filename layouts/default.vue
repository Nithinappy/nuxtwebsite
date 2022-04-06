<template>
  <div>
    <AppHeader />

    <Nuxt />

    <AppFooter />
  </div>
</template>

<script>
import AppFooter from "~/components/inc/AppFooter.vue";
import AppHeader from "~/components/inc/AppHeader.vue";
export default {
  components: { AppHeader, AppFooter },
};
</script>

