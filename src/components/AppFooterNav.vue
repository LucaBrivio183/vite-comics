<script>
import AppFooterLinksVue from './AppFooterLinks.vue';
export default {
    components: {
        AppFooterLinksVue,
    },
    data() {
        return {

        }
    }
}
</script>


<template>
    <section class="footer-nav">
        <div class="container">
            <AppFooterLinksVue />
            <img src="src\assets\img\dc-logo-bg.png" alt="logo-big">
        </div>
    </section>
</template>

<style lang="scss" scoped>
@use '.././styles/partials/variables' as *;
@use '.././styles/partials/_mixins' as *;

.footer-nav {
    padding: 1.875rem 0;
    overflow: hidden;
    @include bgImage('.././assets/img/footer-bg.jpg');

    .container {
        position: relative;

        img {
            position: absolute;
            right: 0;
            top: -150px;
            z-index: 1;
        }
    }

}
</style>