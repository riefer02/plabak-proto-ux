<template>
  <div class="flex flex-wrap flex-col flex-grow overflow-hidden">
    <div class="w-full overflow-hidden flex-grow p-1">
      <AudioDisplay />
    </div>

    <div class="w-full overflow-hidden h-20 p-1">
      <AudioControls />
    </div>
  </div>
</template>

<script>
import AudioControls from "./AudioControls.vue";
import AudioDisplay from "./AudioDisplay.vue";
export default {
  components: {
    AudioControls,
    AudioDisplay,
  },
};
</script>

<style lang="scss" scoped></style>
