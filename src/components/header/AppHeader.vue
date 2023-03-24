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
        <div class="container">
            <AppLogoVue />
            <AppNavbarVue />
        </div>
    </header>
</template>

<style lang="scss" scoped>
@use '../../styles/partials/_variables.scss' as *;
@use '../../styles/partials/_mixins' as *;


.container {
    display: flex;
    justify-content: space-between;
    align-items: center;
}
</style>