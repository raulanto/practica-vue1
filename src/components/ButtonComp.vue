<template>
    <button class=" font-bold px-2 rounded-lg border border-sky-300 bg-sky-600 w-fit text-white py-1 hover:bg-transparent hover:text-sky-300">{{ msg }}</button>
</template>

<script setup lang="ts">
    defineProps<{
    msg: string
    }>()
</script>