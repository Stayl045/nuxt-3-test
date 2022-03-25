<template>
  <header class="flex gap-4 bg-green-200 py-4 justify-items-center">
    <TheLogo />
    <TheNavBar />
  </header>
</template>

<script setup>
  import TheNavBar from "@/components/ui/TheNavBar.vue";
  import TheLogo from "@/components/layout/TheLogo.vue";
</script>
