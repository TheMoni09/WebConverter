<script setup lang="ts">
import Navbar from "@/components/Navbar.vue";
import Uploader from "@/components/Uploader.vue";

</script>

<template>
  <Navbar class="bg-white"/>
  <div class="w-full h-full relative font-['Poppins', serif] flex flex-col md:gap-y-[0.75rem]">
    <Uploader/>
  </div>
</template>

<style scoped>
</style>
