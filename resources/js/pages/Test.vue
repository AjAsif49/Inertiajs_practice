
<template>
    Test
    <br>
    <Footer />
    
    <button @click="count++">+</button>{{ count }}
    <button @click="count--">-</button> 

</template>
    
    <script setup>
    import Footer from "./Footer.vue";
    import { ref } from "vue";
    const count = ref(0);

    </script>