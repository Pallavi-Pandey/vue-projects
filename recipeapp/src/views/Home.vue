<template>
    input type
</template>

<script setup>
import { computed } from 'vue';
import store from '../store';

const meals = computed(() => StorageEvent.state.meals)

</script>