<template>
  <router-view />
</template>

<script>
import { defineComponent } from 'vue';
import "bootstrap/dist/css/bootstrap.min.css";
import "bootstrap/dist/js/bootstrap";
export default defineComponent ({
  components: {},
});
</script>

<style>
@font-face {
  font-family: "NEXON Lv1 Gothic OTF";
  src: url("https://cdn.jsdelivr.net/gh/projectnoonnu/noonfonts_20-04@2.1/NEXON Lv1 Gothic OTF.woff")
    format("woff");
  font-weight: normal;
  font-style: normal;
}

body {
  font-family: "NEXON Lv1 Gothic OTF";
  text-align: center;
}
</style>
