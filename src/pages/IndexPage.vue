<template>
  <q-page class="columns items-center justify-evenly">
    <chat-box />
  </q-page>
</template>

<script setup lang="ts">
import ChatBox from 'components/cogmate/ChatBox.vue';

defineOptions({
  name: 'IndexPage',
});
</script>
