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
@use '.././styles/partials/variables' as *;
@use '.././styles/partials/_mixins' as *;




main {
    background-color: $secondary-color;
    color: $text-color;
    padding: 3.125rem 0;
    margin: 0;
}
</style>