<script>
export default {
    data() {
        return {
            logo: "public/dc-logo.png",
        }
    }
}
</script>

<template>
    <div>
        <img :src="logo" alt="logo" />
    </div>
</template>

<style lang="scss" scoped>
@use 'src/styles/Variables.scss' as *;
@use 'src/styles/Common.scss' as *;

div {
    width: $logo-square-width;
    height: $logo-square-width;
    overflow: hidden;

    img {
        max-width: 100%;
        display: block;
        object-fit: center;
    }
}
</style>