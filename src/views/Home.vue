<template lang="pug">
  v-card
    NavigationBar
</template>

<script>
import NavigationBar from "@/components/NavigationBar.vue";

export default {
  components: {
    NavigationBar,
  },
};
</script>

<style lang="less" scoped>
div {
  width: 100vw;
  height: 100vh;
}
</style>
