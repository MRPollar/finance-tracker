<template>
  <div>
    <NuxtLayout>
      <NuxtPage/>
    </NuxtLayout>
  </div>
</template>

<script setup>
useHead({
  titleTemplate:(title) => title ? `${title} | Finance` : 'Finance',
})
</script>
