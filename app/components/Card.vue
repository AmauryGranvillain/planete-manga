<template>
  <UCard variant="subtle">
    <template #header>
      <UBadge>Badge</UBadge>
    </template>

    <img src="~/assets/img/naruto.jpg" alt="naruto" class="h-48 w-96 object-cover"/>

    <template #footer>
      <UButton><NuxtLink to="manga/naruto">Voir manga</NuxtLink></UButton>
    </template>
  </UCard>
</template>
<script setup lang="ts">
</script>