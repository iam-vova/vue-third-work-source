<template>
    <div class="app_layout">
        <AppLayoutHeader />
        <slot/>
    </div>
</template>

<script setup>
    import AppLayoutHeader from '@/layouts/AppLayoutHeader.vue';
</script>
