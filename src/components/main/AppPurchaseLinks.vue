<script>
import AppPurchaseLinksPropVue from './AppPurchaseLinksProp.vue';
export default {
    name: 'PurchaseLInks',
    components: {
        AppPurchaseLinksPropVue,
    },
    data() {
        return {
            digitalComics: {
                img: 'src/assets/img/buy-comics-digital-comics.png',
                title: 'DIGITAL COMICS',
                link: '#'
            },
            dcMerchandising: {
                img: 'src/assets/img/buy-comics-merchandise.png',
                title: 'DC MERCHANDISING',
                link: '#'
            },
            subscriptions: {
                img: 'src/assets/img/buy-comics-subscriptions.png',
                title: 'SUBSCRIPTION',
                link: '#'
            },
            comicShopLocator: {
                img: 'src/assets/img/buy-comics-shop-locator.png',
                title: 'COMIC SHOP LOCATOR',
                link: '#'
            },
            dcPowerVisa: {
                img: 'src/assets/img/buy-dc-power-visa.svg',
                title: 'DC POWER VISA',
                link: '#'
            }
        }
    }

}
</script>

<template>
    <section>
        <div class="container">
            <AppPurchaseLinksPropVue :img="digitalComics.img" :title="digitalComics.title" :link="digitalComics.link" />
            <AppPurchaseLinksPropVue :img="dcMerchandising.img" :title="dcMerchandising.title"
                :link="dcMerchandising.link" />
            <AppPurchaseLinksPropVue :img="subscriptions.img" :title="subscriptions.title" :link="subscriptions.link" />
            <AppPurchaseLinksPropVue :img="comicShopLocator.img" :title="comicShopLocator.title"
                :link="comicShopLocator.link" />
            <AppPurchaseLinksPropVue :img="dcPowerVisa.img" :title="dcPowerVisa.title" :link="dcPowerVisa.link" />
        </div>
    </section>
</template>

<style lang="scss" scoped>
@use '../../styles/partials/_variables.scss' as *;
@use '../../styles/partials/_mixins' as *;

section {
    background-color: $primary-color;
    padding: 50px 0;

    .container {
        display: flex;
        align-items: center;
        justify-content: center;
    }
}
</style>
