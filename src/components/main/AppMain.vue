<script>
import AppJumbotronVue from './AppJumbotron.vue';
import AppPurchaseLinksVue from './AppPurchaseLinks.vue';
export default {
    components: {
        AppJumbotronVue,
        AppPurchaseLinksVue
    },
    data() {
        return {

        }
    }
}
</script>

<template>
    <main>
        <AppJumbotronVue />
        <AppPurchaseLinksVue />
    </main>
</template>

<style lang="scss" scoped>
@use '../../styles/partials/_variables.scss' as *;
@use '../../styles/partials/_mixins' as *;
</style>