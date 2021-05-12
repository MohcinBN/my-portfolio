<template>
  <div>
    <NavBare msg="Nave bar portfolio" />
    <HelloWorld msg="Hello in my Portfolio" />
    <AboutMe msg="A little aboute me" />
    <Work msg="Some of my works" />
    <Blog msg="Read My blogs" />
    <GetInTouch msg="Connect with me" />
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";
import NavBare from "@/components/NavBare.vue";
import AboutMe from "@/components/AboutMe.vue";
import Work from "@/components/Work.vue";
import Blog from "@/components/Blog.vue";
import GetInTouch from "@/components/GetInTouch.vue";

export default {
  name: "Home",
  components: {
    HelloWorld,
    NavBare,
    AboutMe,
    Work,
    Blog,
    GetInTouch,
  },
};
</script>
