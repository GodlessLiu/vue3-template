<template>
  <TheLogo m="auto"></TheLogo>
  <div>
    <div>
      <button class="btn" @click="go">Hi</button>
    </div>
  </div>
</template>

<script setup lang="ts">
const route = useRouter();
const go = () => {
  route.push("/hi");
};
</script>
