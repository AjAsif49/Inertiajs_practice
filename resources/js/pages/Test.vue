
<template>
        <Layout>Test 
            <br>
            <button @click="count++">+</button>{{ count }}
            <button @click="count--">-</button> 
        </Layout>
</template>
    
    <script setup>
    import Layout from "@/components/Layout.vue";
    import { ref } from "vue";
    const count = ref(0);

    </script>