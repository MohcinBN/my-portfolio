<template>
  <div id="blog">
    <div class="content-wrapper">
      <a
        href="https://bounouara.net/"
        target="_blank"
        rel="noopener noreferrer"
      >
        <span>
          Read my Blog
        </span>
      </a>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
#blog {
  display: flex;
  justify-content: center;
  align-items: center;
  background-color: #a4a2a2;
  padding: 36px 0 41px;
}

#blog .content-wrapper {
  text-align: center;
}

#blog span {
  color: #fff;
  font-weight: bold;
  font-size: 5rem;
  text-transform: uppercase;
  text-align: center;
}

@media (max-width: 700px) {
  #blog span {
    font-size: 2rem;
  }
}
</style>
