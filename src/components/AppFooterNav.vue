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
    <div class="container">
        <AppFooterLinksVue />
    </div>
</template>

<style lang="scss" scoped>
@use '.././styles/partials/variables' as *;
@use '.././styles/partials/_mixins' as *;
@use '.././styles/partials/_typography' as *;
@use '.././styles/partials/_reset' as *;

.container {
    background-color: black;
}
</style>