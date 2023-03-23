<script>
import AppHeaderVue from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import AppFooter from './components/AppFooter.vue';

export default {
  components: {
    AppHeaderVue,
    AppMain,
    AppFooter,
  }
}
</script>

<template>
  <AppHeaderVue />
  <AppMain />
  <AppFooter />
</template>

<style lang="scss" scoped>
@use 'src/styles/Variables.scss' as *;
@use 'src/styles/Common.scss' as *;
</style>
