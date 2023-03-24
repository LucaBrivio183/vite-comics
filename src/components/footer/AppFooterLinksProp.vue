<script>
export default {
    name: "AppFooterLinksProp",
    props: {
        linksTitle: String,
        links: [String]
    }
}
</script>


<template>
    <div>
        <h3>{{ linksTitle }}</h3>
        <ul>
            <li v-for="item in links"><a href="#"> {{ item }}</a></li>
        </ul>
    </div>
</template>


<style lang="scss" scoped>
@use '../../styles/partials/_variables.scss' as *;
@use '../../styles/partials/_mixins' as *;

div {
    h3 {
        color: $text-color;
        padding: 10px 0;
    }

    ul {
        li {
            padding: 5px 0;

            a {
                color: $text-color;
                opacity: 0.8;

                &:hover {
                    opacity: 1;

                }
            }
        }
    }
}
</style>