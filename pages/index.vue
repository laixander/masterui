<template>
    <div class="antialiased flex flex-col items-center justify-start min-h-screen place-content-center p-6 sm:text-base text-sm text-black">
        <UContainer class="w-full p-4 border border-gray-200 rounded-lg shadow-sm bg-white">
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