<script>
import AppHeaderVue from './components/header/AppHeader.vue';
import AppMainVue from './components/main/AppMain.vue';
import AppFooterVue from './components/footer/AppFooter.vue';
import AppFooterNavVue from './components/footer/AppFooterNav.vue';

export default {
  components: {
    AppHeaderVue,
    AppMainVue,
    AppFooterVue,
    AppFooterNavVue,
  }
}
</script>

<template>
  <AppHeaderVue />
  <AppMainVue />
  <AppFooterNavVue />
  <AppFooterVue />
</template>

<style lang="scss" scoped>
@use './styles/partials/variables' as *;
@use './styles/partials/_mixins' as *;
@use './styles/partials/_typography' as *;
@use './styles/partials/_reset' as *;
</style>
