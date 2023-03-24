<script>
import AppHeaderVue from './components/AppHeader.vue';
import AppMainVue from './components/AppMain.vue';
import AppFooterVue from './components/AppFooter.vue';
import AppFooterNavVue from './components/AppFooterNav.vue';

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
