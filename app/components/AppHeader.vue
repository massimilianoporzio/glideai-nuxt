<template>
  <header>header content</header>
</template>

<script lang="ts" setup>
import type { Content } from "@prismicio/client";
defineProps<{
  seetings?: Content.SettingsDocument;
}>();
</script>

<style></style>
