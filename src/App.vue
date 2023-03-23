<script>
import AppHeaderVue from './components/AppHeader.vue';
import AppMainVue from './components/AppMain.vue';
import AppFooterVue from './components/AppFooter.vue';
import AppPreFooterVue from './components/AppPreFooter.vue';

export default {
  components: {
    AppHeaderVue,
    AppMainVue,
    AppFooterVue,
    AppPreFooterVue,
  }
}
</script>

<template>
  <AppHeaderVue />
  <AppMainVue />
  <AppPreFooterVue />
  <AppFooterVue />
</template>

<style lang="scss" scoped>
@use 'src/styles/Variables.scss' as *;
@use 'src/styles/Common.scss' as *;
</style>
