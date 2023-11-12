<template>
  <div>
    <!-- <NuxtLayout name="custom"> -->
    <!-- <NuxtLayout :name="layout">  -->
    <NuxtLayout>
      <NuxtPage />
    </NuxtLayout>
  </div>
</template>

<script setup>
const admin = true;
const layout = admin ? 'custom' : 'default';
</script>
