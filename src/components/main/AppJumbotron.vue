<script>
export default {
    data() {
        return {

        }
    }
}
</script>

<template>
    <section id="jumbotron">

    </section>
</template>

<style lang="scss" scoped>
@use '../../styles/partials/_variables.scss' as *;
@use '../../styles/partials/_mixins' as *;

#jumbotron {
    height: 25rem;
    @include bgImage("src/assets/img/jumbotron.jpg");
    background-position: 50% 0%;
}
</style>