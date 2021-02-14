<template>
  <div class="container mx-auto bg-gray-100 h-screen shadow-lg">
    <div class="flex flex-col overflow-hidden h-screen">
      <div class="w-full shadow-inner">
        <NavMenu />
      </div>
      <div class="w-full overflow-hidden flex-1 bg-indigo-100 shadow-inner">
        <MainContent />
      </div>
      <div class="w-full h-40 flex justify-center shadow-inner">
        <SubMenu />
      </div>
    </div>
  </div>
</template>

<script>
import NavMenu from "./NavMenu.vue";
import SubMenu from "./SubMenu.vue";
import MainContent from "./MainContent.vue";
export default {
  components: {
    NavMenu,
    SubMenu,
    MainContent,
  },
};
</script>

<style lang="scss" scoped></style>
