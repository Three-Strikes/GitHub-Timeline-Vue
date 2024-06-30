<script setup lang="ts">
import SearchInput from './SearchInput.vue'
</script>

<template>
    <div class="navbar">
        <SearchInput />
    </div>
    
</template>

<style scoped>
    .navbar{
        display: flex;
        border-bottom: 1px solid #5343AA;
        width: 100%;
        padding: 10px 0px;
        justify-content: center;
    }

</style>
