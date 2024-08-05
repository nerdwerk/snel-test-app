<script setup></script>

<template>
    <div class="welcome">
        <h1>Some Title</h1>

        <p>Here's some facts about Cats.</p>
    </div>

    <div class="gallery">
        <img src="https://placehold.co/400x400" alt="" />
        <img src="https://placehold.co/400x400" alt="" />
        <img src="https://placehold.co/400x400" alt="" />
        <img src="https://placehold.co/400x400" alt="" />
    </div>
</template>

<style scoped>
    .container {
        width: 100%;
        margin-left: auto;
        margin-right: auto;
        max-width: 60rem;
    }

    .gallery {
        display: grid;
        grid-template-columns: repeat(2, minmax(0, 1fr));
        gap: 1rem;
    }

    .gallery img {
        max-width: 20rem;
        max-height: 20rem;
    }
</style>
