<template>
  <!-- <div>
    <NuxtLayout name='custom'>
      <h1>Main Page</h1>
    </NuxtLayout>
  </div> -->
  <div>
    <button @click="enableCustomLayout">Update layout</button>
  </div>
</template>

<script setup>
// function enableCustomLayout() {
//   setPageLayout('custom');
// }
const route = useRoute();
const enableCustomLayout = () => {
  route.meta.layout = 'custom';
};
definePageMeta({
  layout: 'false',
});
</script>
