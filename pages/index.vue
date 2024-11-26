<template>
    <div class="antialiased bg-white dark:bg-black dark:text-white flex flex-col items-center justify-center min-h-screen place-content-center sm:text-base text-black text-sm">

        <UContainer class="w-full mt-8 p-4 border border-gray-200 rounded-lg shadow-sm bg-white">
        <div class="text-gray-600 flex items-center gap-3">
            <UIcon name="i-heroicons-home" class="w-5 h-5" /> Hello World
        </div>
    </UContainer>
    </div>
</template>

<script setup>
useHead({
    bodyAttrs: {
        class: ['bg-gray-50']
    },
});
</script>

<style scoped>

</style>