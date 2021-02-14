<template>
  <div class="w-1/4 h-auto flex justify-center items-center">
    <button class="p-1">
      <ion-icon :name="icon"></ion-icon>
    </button>
  </div>
</template>

<script>
export default {
  props: {
    icon: {
      type: String,
      default: "share-social-outline",
    },
  },
};
</script>

<style scoped>
ion-icon {
  font-size: 64px;
}
</style>
