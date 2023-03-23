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
@use 'src/styles/Variables.scss' as *;
@use 'src/styles/Common.scss' as *;
</style>
