<template>
    <section>
        <router-link to="/" active-class="text-primary">Home</router-link>
        <span class="px-3">|</span>
        <router-link to="about" active-class="text-primary">About</router-link>
    </section>

    <router-view></router-view>
</template>

<!-- <script lang="ts">
import { defineComponent } from 'vue'
export default defineComponent({})
</script> -->

<!-- <script setup lang="ts"></script> -->
