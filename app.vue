<script setup>
import { onMounted } from 'vue';
const route = useRoute()
onMounted(() => {
    document.getElementById("container").setAttribute("data-theme", "cupcake");
});
</script>

<template>
    <div class="flex flex-col w-full h-auto" id="container">
        <div v-if="route.path !== '/'">
            <Nav />
        </div>
        <NuxtPage />
    </div>
    <div v-if="route.path !== '/'">
        <Footer />
    </div>
</template>
