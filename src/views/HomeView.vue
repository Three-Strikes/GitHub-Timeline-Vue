
<script setup lang="ts">
import NavBar from '../components/NavBar.vue';
</script>

<template>

    <NavBar/>
    <div id="main-content" class="main-content">
        <h1>GitHub timeline Viewer!</h1>
        <h4>With this tool, you can view the GitHub timeline of anyone!</h4>
    </div>

</template>


<style>
    .main-content {
        display: flex;
        flex-direction: column;
        justify-content: center;
        width: 100% ; 
        align-items: center;
        height: 100% !important;
    }

    h1 {
        font-size: 82px;
    }

    h4 {
        font-size: 40px;
    }

    
</style>
