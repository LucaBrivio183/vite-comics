<script>
import AppFooterLinks from './AppFooterLinks.vue';
import AppFooterSocialsVue from './AppFooterSocials.vue';

export default {
    components: {
        AppFooterLinks,
        AppFooterSocialsVue,
    },
    data() {
        return {

        }
    }
}
</script>

<template>
    <footer>
        <AppFooterLinks />
        <AppFooterSocialsVue />
    </footer>
</template>

<style lang="scss" scoped>
@use 'src/styles/Variables.scss' as *;
@use 'src/styles/Common.scss' as *;
</style>