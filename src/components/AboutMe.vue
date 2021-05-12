<template>
  <div id="about-me" class="section">
    <article class="about-me-note content-wrapper">
      <h2 class="section-title">A little aboute me</h2>
      <p>
        Mohcin Bounouara, more than 3 years of professional experience as a Web
        Developer/Software Developer in analysis, design, Improve UI & UX,
        caring about web performance and web accessibility.
        <br />
        With ability to learn from experienced experts and improve myself in web
        development and software engineering.
        <br />
        I believe in those;
      </p>
      <blockquote>
        "Share what you learned, sharing is knowledge" -Mohcin
      </blockquote>
      <blockquote>"Small acts make big impacts" -Anonymouse</blockquote>
      <h3>Tools and technology used recently:</h3>
      <ul>
        <li>
          <img src="@/assets/images/javascript.png" alt="javascript icon" />
        </li>
        <li>
          <img src="@/assets/images/html-5--v2.png" alt="html 5 icon" />
        </li>
        <li>
          <img src="@/assets/images/css3.png" alt="css 3 icon" />
        </li>
        <li>
          <img src="@/assets/images/webpack.png" alt="webpack icon" />
        </li>
        <li>
          <img src="@/assets/images/vue-js.png" alt="vue js icon" />
        </li>
        <li>
          <img src="@/assets/images/jquery.png" alt="jquery icon" />
        </li>
        <li>
          <img src="@/assets/images/php-logo.png" alt="php icon" />
        </li>
        <li>
          <img src="@/assets/images/laravel.png" alt="laravel icon" />
        </li>
        <li>
          <img src="@/assets/images/mysql-logo.png" alt="mysql icon" />
        </li>
        <li>
          <img src="@/assets/images/wordpress.png" alt="wordpress icon" />
        </li>
        <li>
          <img src="@/assets/images/woocommerce.png" alt="woocommerce icon" />
        </li>
        <li>
          <img src="@/assets/images/bootstrap.png" alt="bootstrap icon" />
        </li>
      </ul>
    </article>
  </div>
</template>

<script>
export default {};
</script>

<style>
#about-me {
  display: flex;
  justify-content: center;
  align-items: center;
}
.about-me-note {
  width: 70vw !important;
}
.about-me-note {
  font-size: 1.2rem;
  line-height: 3;
}
ul {
  display: flex;
  list-style: none;
  padding-left: 0;
}
ul > li > img {
  width: 50%;
  filter: grayscale(1);
  cursor: pointer;
}

ul > li > img:hover {
  filter: none;
}

@media (max-width: 700px) {
  .about-me-note {
    font-size: 1rem;
    line-height: 2;
    width: inherit !important;
    margin-top: 25px;
  }
  #about-me ul {
    display: block;
    text-align: center;
  }
  #about-me ul > li > img {
    width: 31%;
  }
}
</style>
