<script lang="ts" setup>
const { title, description, imagePath } = defineProps<{
  title?: string;
  description?: string;
  imagePath: string;
}>();
</script>

<template>
  <div>
    <img :src="imagePath" alt="Image" />
    <div class="main">
      <h1>
        {{ title }}
      </h1>
      <p>
        {{ description }}
      </p>
  </div>
</template>
