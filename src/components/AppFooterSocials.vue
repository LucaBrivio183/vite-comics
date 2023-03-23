<script>
import AppButtonVue from './AppButton.vue';
import AppFooterSocialLinksVue from './AppFooterSocialLinks.vue';

export default {
    components: {
        AppButtonVue,
        AppFooterSocialLinksVue,
    },
    data() {
        return {

        }
    }
}
</script>

<template>
    <div>
        <AppButtonVue />
        <AppFooterSocialLinksVue />
    </div>
</template>

<style lang="scss" scoped>
@use 'src/styles/Variables.scss' as *;
@use 'src/styles/Common.scss' as *;

div {
    background-color: $tertiary-color;
    display: flex;
    justify-content: space-between;
    padding: 1.875rem 0;
}
</style>