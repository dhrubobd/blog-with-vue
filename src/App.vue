<script setup>
import { RouterLink,RouterView } from 'vue-router';
</script>

<template>
    <div>
        <nav>
            <ul>
                <li>
                    <RouterLink to="/">Home</RouterLink>
                </li>
                <li>
                    <RouterLink to="/about">About</RouterLink>
                </li>
            </ul>
        </nav>
        <RouterView />
    </div>
</template>

<style scoped>

</style>
