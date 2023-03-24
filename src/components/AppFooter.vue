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
    <footer>
        <div class="container">
            <AppButtonVue />
            <AppFooterSocialsVue />
        </div>
    </footer>
</template>

<style lang="scss" scoped>
@use '.././styles/partials/variables' as *;
@use '.././styles/partials/_mixins' as *;



footer {
    background-color: $tertiary-color;

    .container {
        display: flex;
        justify-content: space-between;
        padding: 1.875rem 0;
    }
}
</style>