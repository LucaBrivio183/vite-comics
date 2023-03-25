<script>
export default {
    name: 'PurchaseLInksProp',
    props: {
        img: String,
        title: String,
        link: String
    }
}
</script>

<template>
    <a :href="link">
        <div><img :src="img"></div>
        <h4>{{ title }}</h4>
    </a>
</template>

<style lang="scss" scoped>
@use '../../styles/partials/_variables.scss' as *;
@use '../../styles/partials/_mixins' as *;

a {
    display: flex;
    align-items: center;
    color: $text-color;
    opacity: 0.8;
    padding: 0 .625rem;
    gap: .625rem;

    &:hover {
        opacity: 1;

    }

    h4 {
        font-size: 1rem;
    }

    div {
        display: flex;
        align-items: center;
        justify-content: center;

        img {
            width: 3.125rem;
            height: 4.375rem;
        }
    }
}
</style>