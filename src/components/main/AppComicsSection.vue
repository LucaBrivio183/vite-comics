<script>
import AppComicsListVue from './AppComicsList.vue';
export default {
    components: {
        AppComicsListVue
    }
}
</script>

<template>
    <section>
        <div class="container">
            <AppComicsListVue />
        </div>
    </section>
</template>

<style lang="scss" scoped>
@use '../../styles/partials/_variables.scss' as *;
@use '../../styles/partials/_mixins' as *;

section {
    background-color: $secondary-color;
    padding: 20px 0;
}
</style>