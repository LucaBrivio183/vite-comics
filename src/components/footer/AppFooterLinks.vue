<script>
import AppFooterLinkPropVue from './AppFooterLinksProp.vue';
export default {
    name: "AppFooterLinks",
    components: {
        AppFooterLinkPropVue,
    },
    data() {
        return {
            dcComicsLinks: {
                linksTitle: 'DC COMICS',
                links: [
                    "Characters",
                    "Comics",
                    "Movies",
                    "TV",
                    "Games",
                    "Videos",
                    "News"
                ]
            },
            shopLinks: {
                linksTitle: 'SHOP',
                links: [
                    "Shop DC",
                    "Shop DC Collectibles"
                ]
            },
            dcLinks: {
                linksTitle: 'DC',
                links: [
                    "Terms Of Use",
                    "Privacy Policy (New)",
                    "Ad Choices",
                    "Advertising",
                    "Jobs",
                    "Subscriptions",
                    "Talent Workshops",
                    "CPSC Certificates",
                    "Ratings",
                    "Shop Help",
                    "Contact Us"
                ]
            },
            sitesLinks: {
                linksTitle: 'SITES',
                links: [
                    "DC",
                    "MAD Magazine",
                    "DC Kids",
                    "DC Universe",
                    "DC Power Visa"
                ]
            }
        }
    }
}
</script>

<template>
    <div class="flex-row">
        <div class="col">
            <AppFooterLinkPropVue :linksTitle="dcComicsLinks.linksTitle" :links="dcComicsLinks.links" />
            <AppFooterLinkPropVue :linksTitle="shopLinks.linksTitle" :links="shopLinks.links" />
        </div>
        <div class="col">
            <AppFooterLinkPropVue :linksTitle="dcLinks.linksTitle" :links="dcLinks.links" />
        </div>
        <div class="col">
            <AppFooterLinkPropVue :linksTitle="sitesLinks.linksTitle" :links="shopLinks.links" />
        </div>
    </div>
</template>

<style lang="scss" scoped>
@use '../../styles/partials/_variables.scss' as *;
@use '../../styles/partials/_mixins' as *;

.flex-row {
    display: flex;
    gap: 1.25rem;
    z-index: 2;
}
</style>