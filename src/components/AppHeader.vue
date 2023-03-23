<script>
import AppNavbarVue from './AppNavbar.vue';
import AppLogoVue from './AppLogo.vue';
export default {
    components: {
        AppNavbarVue,
        AppLogoVue,
    },
    data() {
        return {

        }
    }
}
</script>

<template>
    <header>
        <AppLogoVue />
        <AppNavbarVue />
    </header>
</template>

<style lang="scss" scoped>
@use 'src/styles/Variables.scss' as *;
@use 'src/styles/Common.scss' as *;
</style>