<template>
    <div class="p-5 bg-gray-200">
        <router-link :to="{ name: 'Home' }">Home</router-link>
        <router-link :to="{ name: 'Register' }">Register</router-link>
    </div>
    <RouterView></RouterView>
</template>

<script setup>

</script>

