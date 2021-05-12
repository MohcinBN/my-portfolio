<template>
  <div>
    <NavBare msg="Nave bar portfolio" />
    <HelloWorld msg="Welcome to Your Vue.js App" />
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";
import NavBare from "@/components/NavBare.vue";

export default {
  name: "Home",
  components: {
    HelloWorld,
    NavBare,
  },
};
</script>
