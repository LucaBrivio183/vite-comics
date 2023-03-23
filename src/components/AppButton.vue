<script>

export default {

    data() {
        return {
            button:
            {
                name: 'SIGN-UP NOW!',
                link: '#',
                target: '_self',
            }
        }
    }
}
</script>

<template>
    <a :href="button.link">{{ button.name }}</a>
</template>

<style lang="scss" scoped>
@use 'src/styles/Variables.scss' as *;
@use 'src/styles/Common.scss' as *;

a {
    display: inline-block;
    text-decoration: none;
    padding: 15px;
    color: $text-color;
    border: 2px solid $primary-color;

    &:hover {
        background-color: $primary-color;
        color: $secondary-color;
    }
}
</style>