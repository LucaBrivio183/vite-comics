<script>
export default {
    data() {
        return {

        }
    }
}
</script>

<template>
    <main>
        <p> ----- Content goes here ----- </p>
    </main>
</template>

<style lang="scss" scoped>
@use 'src/styles/Variables.scss' as *;
@use 'src/styles/Common.scss' as *;

main {
    background-color: $secondary-color;
    color: $text-color;
    padding: 3.125rem 0;
    margin: 0;
}
</style>