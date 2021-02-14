<template>
  <nav class="flex flex-wrap flex-grow">
    <NavButton icon="person-circle-outline" />
    <NavButton icon="library-outline" />
    <NavButton icon="search-circle-outline" />
    <NavButton icon="share-social-outline" />
  </nav>
</template>

<script>
import NavButton from "./NavButton.vue";
export default {
  components: {
    NavButton,
  },
};
</script>

<style lang="scss" scoped></style>
