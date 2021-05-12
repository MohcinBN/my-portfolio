<template>
  <div
    id="home"
    class="section"
    :style="{
      'background-image': 'url(' + require('@/assets/images/bg-2.jpg') + ')',
      'background-size': 'cover',
      'background-position': 'center',
      'background-repeat': 'no-repeat',
      filter: 'brightness(0.6)',
    }"
  >
    <main class="content-wrapper">
      <div class="welcoming">
        <h1>Assalamo Alaykom</h1>
        <h2>I'm</h2>
        <h3>Mohcin.</h3>
        <span>Software Developer</span>
      </div>
    </main>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
#home {
  display: flex;
  justify-content: center;
  align-items: center;
}
main {
  display: flex;
  align-items: center;
  justify-content: center;
  width: 77vw !important;
  color: #fff;
}
.personal-image img {
  width: 300px;
  border: 3px solid #fff;
  border-radius: 11px;
  transition: 0.3s ease-in;
}
.personal-image img:hover {
  transform: scale(1.2);
}
.welcoming h1,
.welcoming h2 {
  font-weight: 300;
  font-size: 3rem;
  line-height: 21px;
}
.welcoming h1 {
  background: rgba(0, 0, 0, 0.5);
  padding: 25px 13px 25px 13px;
}
.welcoming h3 {
  font-weight: bold;
  font-size: 4rem;
  line-height: 0;
}
.welcoming span {
  background: #fff;
  color: #222;
  width: 100%;
  display: block;
  text-align: center;
  padding: 11px;
  font-weight: bold;
  cursor: pointer;
  transition: 0.3s ease-in;
  font-size: 2rem;
}
.welcoming span:hover {
  background: #527751;
  color: #fff;
}
</style>
