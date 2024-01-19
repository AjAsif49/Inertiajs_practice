<template>
    <header>
        <span> My app </span>
        <Link href="/about" name="About" component="About"></Link>
        <Link href="/test" name="Test" component="Test"></Link>
        <button>Login</button>
    </header>

    <slot></slot>

    <Footer/>
</template>

<script setup>
        import Footer from "@/components/Footer.vue";
        import Link from "@/components/Link.vue";
</script>