<script>
import AppJumbotronVue from './AppJumbotron.vue';
import AppPurchaseLinksVue from './AppPurchaseLinks.vue';
import AppComicsSectionVue from './AppComicsSection.vue';
export default {
    components: {
        AppJumbotronVue,
        AppPurchaseLinksVue,
        AppComicsSectionVue
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
        <AppComicsSectionVue />
        <AppPurchaseLinksVue />
    </main>
</template>

<style lang="scss" scoped>
@use '../../styles/partials/_variables.scss' as *;
@use '../../styles/partials/_mixins' as *;
</style>