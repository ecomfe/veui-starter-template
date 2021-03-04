<template>
  <div id="app">
    <h1>Welcome to VEUI.</h1>
    <v-button>OK</v-button>
  </div>
</template>

<script>
import { VButton } from "veui";

export default {
  name: "App",
  components: {
    VButton
  }
};
</script>

<style lang="less">
#app {
  text-align: center;
  margin-top: 30vh;
}
</style>
