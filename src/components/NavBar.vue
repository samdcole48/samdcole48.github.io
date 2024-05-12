<script setup>
</script>

<template>
    <div class="navBarContainer">
        <img class="logo" src='@\assets\logo-noBackground.png'>
        <div class="pages">
            <a>About</a>
            <a>Qualifications</a>
            <a>Portfolio</a>
        </div>
    </div>
</template>

<style scoped>
.navBarContainer {
    background-color: black;
    display: flex;
    justify-content: space-between;
    align-items: center;
    width: 100vw;
}
.logo {
    width: 100px; /*need to rethink about sizing, possibly min and max height */
    height: auto;
}
a {
}
</style>