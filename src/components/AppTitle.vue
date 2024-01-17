<script>
    export default {
        data() {
            return {
                title: 'La mia prima app con Vite!'
            }
        }
    };
</script>

<template>
    <header>
        <h1 class="main-title">
            {{ title }}
        </h1>
    </header>
</template>

<style scoped>
header {
    color: blue;
    font-size: 16px;
}
</style>
