<template>
  <div>
    <HelloWorld />
  </div>
</template>

<script lang="ts">
import { Options, Vue } from "vue-class-component";
import HelloWorld from "./components/HelloWorld.vue";

@Options({
  components: {
    HelloWorld,
  },
})
export default class App extends Vue {}
</script>

<style>
#app {
  margin-top: -22px !important;
  color: rgb(90, 90, 90);
}
</style>
