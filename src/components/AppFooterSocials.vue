<script>
export default {
    data() {
        return {
            socialList: [
                {
                    name: 'facebook',
                    logo: 'src/assets/img/footer-facebook.png',
                    link: '#',
                    target: '_self',
                }, {
                    name: 'twitter',
                    logo: 'src/assets/img/footer-twitter.png',
                    link: '#',
                    target: '_self',
                }, {
                    name: 'youtube',
                    logo: 'src/assets/img/footer-youtube.png',
                    link: '#',
                    target: '_self',
                }, {
                    name: 'pinterest',
                    logo: 'src/assets/img/footer-pinterest.png',
                    link: '#',
                    target: '_self',
                }, {
                    name: 'periscope',
                    logo: 'src/assets/img/footer-periscope.png',
                    link: '#',
                    target: '_self',
                },
            ],
        }
    }
}
</script>

<template>
    <div>
        <span>FOLLOW US</span>
        <ul>
            <li v-for="item in socialList"><a :href="item.link"><img :src="item.logo" alt="item.name"></a></li>
        </ul>
    </div>
</template>

<style lang="scss" scoped>
@use '.././styles/partials/variables' as *;
@use '.././styles/partials/_mixins' as *;
@use '.././styles/partials/_typography' as *;
@use '.././styles/partials/_reset' as *;



div {
    display: flex;
    align-items: center;

    span {
        padding: 0 1rem;
        font-size: 1.25rem;
        font-weight: bold;
        color: $primary-color;
    }

    ul {
        display: flex;
        list-style-type: none;
        gap: .625rem;

        li {


            a {
                display: flex;
                align-items: center;
                justify-content: center;
                text-decoration: none;
                width: 50px;
                height: 50px;

                img {
                    max-width: 100%;
                    object-fit: center;
                }
            }
        }
    }
}
</style>