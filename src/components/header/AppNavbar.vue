<script>
export default {
    data() {
        return {
            menuList: [
                {
                    name: 'CHARACTERS',
                    link: '#',
                    target: '_self',
                }, {
                    name: 'COMICS',
                    link: '#',
                    target: '_self',
                }, {
                    name: 'MOVIES',
                    link: '#',
                    target: '_self',
                }, {
                    name: 'TV',
                    link: '#',
                    target: '_self',
                }, {
                    name: 'GAMES',
                    link: '#',
                    target: '_self',
                }, {
                    name: 'COLLECTIBLES',
                    link: '#',
                    target: '_self',
                }, {
                    name: 'VIDEOS',
                    link: '#',
                    target: '_self',
                }, {
                    name: 'FANS',
                    link: '#',
                    target: '_self',
                }, {
                    name: 'NEWS',
                    link: '#',
                    target: '_self',
                }, {
                    name: 'SHOP',
                    link: '#',
                    target: '_self',
                },
            ],
        }
    }
}
</script>

<template>
    <nav>
        <ul>
            <li v-for="item in menuList"><a :href="item.link">{{ item.name }}</a></li>
        </ul>
    </nav>
</template>

<style lang="scss" scoped>
@use '../../styles/partials/_variables.scss' as *;
@use '../../styles/partials/_mixins' as *;

nav {
    ul {
        display: flex;
        list-style-type: none;
        gap: 1.875rem;

        li {
            a {
                display: inline-block;
                text-decoration: none;
                color: $tertiary-color;
                padding: 3.125rem 0;

            }

            &:hover {
                color: $primary-color;
                border-bottom: 5px solid $primary-color;
            }
        }
    }
}
</style>