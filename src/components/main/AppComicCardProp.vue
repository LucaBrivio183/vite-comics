<script>
export default {
    name: "ComicCardProp",
    props: {
        img: String,
        title: String
    }
}
</script>

<template>
    <div class="card">
        <div> <img :src="img" :alt="title"></div>
        <h3>{{ title }}</h3>
    </div>
</template>

<style lang="scss" scoped>
@use '../../styles/partials/_variables.scss' as *;
@use '../../styles/partials/_mixins' as *;

.card {
    padding: 13px;
    width: calc(100%/6);

    div {
        overflow: hidden;
        max-height: 200px;

        img {
            object-fit: center;
        }
    }

    h3 {
        color: $text-color;
        font-size: .75rem;
        line-height: .875rem;
        padding: .75rem 0;
    }
}
</style>
