<script>
import AppButtonVue from './AppButton.vue';
import AppFooterSocialsVue from './AppFooterSocials.vue';

export default {
    components: {
        AppButtonVue,
        AppFooterSocialsVue,
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
        <AppFooterSocialsVue />
    </div>
</template>

<style lang="scss" scoped>
@use '.././styles/partials/variables' as *;
@use '.././styles/partials/_mixins' as *;



div {
    background-color: $tertiary-color;
    display: flex;
    justify-content: space-between;
    padding: 1.875rem 0;
}
</style>