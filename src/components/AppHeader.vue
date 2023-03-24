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
@use '.././styles/partials/variables' as *;
@use '.././styles/partials/_mixins' as *;


header {
    display: flex;
    justify-content: space-between;
    align-items: center;
}
</style>