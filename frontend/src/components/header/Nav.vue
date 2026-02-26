<script setup lang="ts">

const navigations = [
    'Home',
    'How to use',
    'Profile'
]

</script>

<template>

<nav>
    <ul>
        <li v-for="nav in navigations" :key="nav"> {{ nav }}</li>
    </ul>
</nav>

</template>

<style>

nav ul {
    display: flex;
    list-style: none;
    gap: 10px;
}

</style>