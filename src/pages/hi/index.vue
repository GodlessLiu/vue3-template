<template>
  <div>This is a introduce for Laf-vue-demo</div>
  <div m="t-4">
    <button class="btn" @click="goBack">Back</button>
  </div>
</template>

<script setup lang="ts">
const route = useRouter();
const goBack = () => {
  route.go(-1);
};
</script>
