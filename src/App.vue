<template>
  <div>
    <h1>{{ msg }}</h1>
    <hello-world />
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";

export default {
  name: "App",
  components: {
    HelloWorld
  },
  data() {
    return {
      msg: "Starter Template for Parcel and VueJS"
    };
  }
};
</script>

<style>
div {
  margin: 0 auto;
}
</style>
