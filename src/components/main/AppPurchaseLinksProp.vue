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
        img {
            object-fit: center;
            height: 3.75rem;
            width: auto;
        }
    }
}
</style>