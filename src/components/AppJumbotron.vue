<script>
export default {
    data() {
        return {
            picName: 'darth'
        }
    },
    methods: {
        getImagePath(picName) {
            const url = new URL(`../assets/${picName}.png`, import.meta.url)

            return url.href;
        }
    }
}
</script>

<template>
    <jumbotron>
        <img :src="getImagePath(picName)" alt="Darth Vader">
    </jumbotron>
</template>

<style>
img {
    max-width: 1200px;
    display: block;
    object-fit: cover;
}
</style>