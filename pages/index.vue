<template>
    <div class="bg-white">
        <Slider v-model="value" class="w-56" />
    </div>
</template>

<script setup>
import { ref } from 'vue';

const value = ref(null);
</script>

