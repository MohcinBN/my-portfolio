<template>
  <div>
    <NavBare msg="Nave bar portfolio" />
    <HelloWorld msg="Hello in my Portfolio" />
    <AboutMe msg="A little aboute me" />
    <Work msg="Some of my works" />
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";
import NavBare from "@/components/NavBare.vue";
import AboutMe from "@/components/AboutMe.vue";
import Work from "@/components/Work.vue";

export default {
  name: "Home",
  components: {
    HelloWorld,
    NavBare,
    AboutMe,
    Work,
  },
};
</script>
