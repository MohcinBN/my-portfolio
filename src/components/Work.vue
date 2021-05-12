<template>
  <div id="work" class="section">
    <div class="grid content-wrapper">
      <h2 class="section-title">Some of my recent work</h2>
      <article class="work-item">
        <h2 class="description">A website for small services</h2>
        <span class="tools">Tools: Vue Js - HTML/CSS</span>
        <br />
        <a href="https://bricobing.ma" target="_blank">bricobing.ma</a>
      </article>
      <article class="work-item">
        <h2 class="description">An Islamic Website</h2>
        <span class="tools">Tools: Laravel - PHP - HTML/CSS</span>
        <br />
        <a href="http://read1hadith.com/" target="_blank">read1hadith.com</a>
      </article>
      <article class="work-item">
        <h2 class="description">
          A Simple online notepad - write and doawnload your notes
        </h2>
        <span class="tools">Tools: Vue Js - HTML/CSS</span>
        <br />
        <a href="https://bounouara.net/online-notepad/" target="_blank"
          >online notepad</a
        >
      </article>
      <article class="work-item">
        <h2 class="description">Ecommerce website</h2>
        <span class="tools">Tools: Wordpress - PHP - jQuery</span>
        <br />
        <a href="https://aljamalrituals.com/" target="_blank"
          >aljamalrituals.com</a
        >
      </article>
      <article class="work-item">
        <h2 class="description">Enterprise website</h2>
        <span class="tools">Tools: Wordpress - PHP - HTML/CSS</span>
        <br />
        <a href="https://mytapisserie.ma/" target="_blank">mytapisserie.ma</a>
      </article>
      <article class="work-item">
        <h2 class="description">Real estate website</h2>
        <span class="tools">Tools: Wordpress - PHP - HTML/CSS</span>
        <br />
        <a href="http://rawan.ma/" target="_blank">rawan.ma</a>
      </article>
      <article class="work-item">
        <h2 class="description">Small tool to export image from text</h2>
        <span class="tools">Tools: Vue js - HTML/CSS</span>
        <br />
        <a href="http://bounouara.net/text-to-downlable-image/" target="_blank"
          >Text to Image</a
        >
      </article>
      <article class="work-item">
        <h2 class="description">Ecommerce website</h2>
        <span class="tools">Tools: Wordpress - PHP - jQuery</span>
        <br />
        <a href="https://labelcuisine.ma/" target="_blank">labelcuisine.ma</a>
      </article>
      <article class="work-item">
        <h2 class="description">News website (burkina faso)</h2>
        <span class="tools">Tools: Wordpress - PHP - jQuery</span>
        <br />
        <a href="https://liberationburkina.net" target="_blank"
          >liberationburkina.net</a
        >
      </article>
      <article class="work-item">
        <h2 class="description">Real estate website</h2>
        <span class="tools">Tools: PHP - HTML/CSS/JS</span>
        <br />
        <a href="http://www.zenith-hills.ma/" target="_blank"
          >zenith-hills.ma</a
        >
      </article>
      <article class="work-item">
        <h2 class="description">Real estate website</h2>
        <span class="tools">Tools: PHP - HTML/CSS/JS</span>
        <br />
        <a href="hhttp://bo52.ma/" target="_blank">bo52.ma</a>
      </article>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
#work {
  display: flex;
  justify-content: center;
  align-items: center;
  background-color: #dbc7db;
  position: relative;
}
.grid {
  display: flex;
  justify-content: space-between;
  flex-wrap: wrap;
}
@media (max-width: 400px) {
  .grid {
    display: block;
  }
}
.work-item {
  background: #fff;
  border-radius: 23px;
  padding: 12px 21px 12px 21px;
  flex: auto;
  margin-right: 2%;
  margin-top: 30px;
}

.work-item h2 {
  line-height: 0;
  font-weight: 400;
}
.grid .section-title {
  position: absolute;
  top: 24px;
}
@media (max-width: 700px) {
  .work-item h2 {
    line-height: 1;
  }
  #work {
    padding: 54px 0 54px;
  }
}
</style>
