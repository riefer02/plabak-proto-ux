<template>
  <div class="flex flex-wrap overflow-hidden">
    <div class="w-1/5 overflow-hidden flex justify-center items-center">
      <ion-icon name="home-outline"></ion-icon>
    </div>

    <div class="w-3/5 overflow-hidden p-1">
      <ProgressBar />
      <AudioMeta />
    </div>

    <div class="w-1/5 overflow-hidden flex justify-center items-center">
      <ion-icon name="volume-high-outline"></ion-icon>
    </div>
  </div>
</template>

<script>
import ProgressBar from "./ProgressBar.vue";
import AudioMeta from "./AudioMeta.vue";
export default {
  components: {
    ProgressBar,
    AudioMeta,
  },
};
</script>

<style scoped>
ion-icon {
  font-size: 48px;
}
</style>
