<template>
  <header id="nav">
    <div class="content-wrapper">
      <div class="logo">
        <a href="/portfolio"><h2 style="text-decoration: none;">MB</h2></a>
      </div>
      <div class="menu">
        <button @click="toggle"><i class="fas fa-bars"></i></button>
        <nav class="slidfromright" :class="open ? 'open' : ''">
          <ul>
            <button class="close-btn" @click="toggle">
              <i class="fas fa-times"></i>
            </button>
            <li><a @click="toggle" href="#about-me">About Me</a></li>
            <li><a @click="toggle" href="#work">Work</a></li>
            <li><a @click="toggle" href="#blog">Blog</a></li>
            <li><a @click="toggle" href="#get-in-touch">Contact</a></li>
          </ul>
        </nav>
      </div>
    </div>
  </header>
</template>

<script>
export default {
  data() {
    return {
      open: false,
    };
  },
  methods: {
    toggle() {
      this.open = !this.open;
    },
  },
};
</script>

<style>
#nav {
}
.logo {
  text-align: left;
}
.menu {
  text-align: right;
}

#nav button {
  background: transparent;
  border: 0;
}

.slidfromright {
  position: fixed;
  width: 100%;
  transition: all 0.5s ease-in-out;
  right: -100%;
  background: #fff;
  height: 100%;
  box-shadow: 1px 1px 10px rgba(0, 0, 0, 0.5);
  top: 0;
}

.open {
  right: 0;
}

#nav nav button svg {
  color: black;
  position: absolute;
  right: 22px;
}

#nav nav ul {
  display: block;
  text-align: center;
}

#nav ul > li {
  margin-right: 0;
}
#nav ul > li > a {
  font-size: 4rem;
}

@media (max-width: 700px) {
  .welcoming h1,
  .welcoming h2 {
    font-size: 29px;
    line-height: 1;
  }
  .welcoming span {
    font-size: 28px;
  }
  #nav nav ul {
    display: block;
    text-align: center;
  }
  #nav nav ul > li {
    margin-right: 0;
  }
}
</style>
