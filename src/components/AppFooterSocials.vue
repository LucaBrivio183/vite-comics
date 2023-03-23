<script>
import AppButtonVue from './AppButton.vue';
export default {
    components: {
        AppButtonVue,
    },
    data() {
        return {

        }
    }
}
</script>

<template>
    <div>
        <AppButtonVue />
    </div>
</template>

<style lang="scss" scoped>
@use 'src/styles/Variables.scss' as *;
@use 'src/styles/Common.scss' as *;

div {
    background-color: $tertiary-color;
    display: flex;
    justify-content: space-between;
    padding: 1.875rem 0;
}
</style>