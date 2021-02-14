<template>
  <div id="myProgress">
    <div id="myBar"></div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      i: 0,
    };
  },
  methods: {
    move() {
      if (this.i == 0) {
        this.i = 1;
        var elem = document.getElementById("myBar");
        var width = 1;
        var id = setInterval(frame, 10);
        function frame() {
          if (width >= 100) {
            clearInterval(id);
            this.i = 0;
          } else {
            width++;
            elem.style.width = width + "%";
          }
        }
      }
    },
  },
};
</script>

<style scoped>
#myProgress {
  width: 100%;
  background-color: grey;
}

#myBar {
  width: 1%;
  height: 30px;
  background-color: green;
}
</style>
