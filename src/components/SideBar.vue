<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <div class="greetings">
    <h1 class="green">Nyx Gonzalez</h1>
    <h3>
      Hi, I'm Nyx! Game Developer and Software Engineer looking for work.
    </h3>
  </div>
  <nav>
    <RouterLink to="/">
      <span class="material-icons">home</span>
      <span class="text">Home</span>
    </RouterLink>
    <RouterLink to="/games">
      <span class="material-icons">videogame_asset</span>
      <span class="text">Games</span>
    </RouterLink>
    <RouterLink to="/projects">
      <span class="material-icons">code</span>
      <span class="text">Projects</span>
    </RouterLink>
    <RouterLink to="/about">
      <span class="material-icons">person</span>
      <span class="text">About</span>
    </RouterLink>
  </nav>
  <div class="social-media">
    <a href="https://github.com/WitherKNyx">
      <img alt="GitHub" class="logo" src="@/assets/github.svg" width="40" height="40" />
    </a>
    <a href="https://twitter.com/AstralLichen">
      <img alt="Twitter" class="logo" src="@/assets/twitter.svg" width="40" height="40" />
    </a>
    <a href="https://witherk.itch.io/">
      <img alt="Itch.io" class="logo" src="@/assets/itchio.svg" width="40" height="40" />
    </a>
    <a href="https://www.linkedin.com/in/nyx-gonzalez/">
      <img alt="LinkedIn" class="logo" src="@/assets/linkedin.svg" width="40" height="40" />
    </a>
    <a href="mailto:nyxgonz@gmail.com">
      <img alt="Email" class="logo" src="@/assets/email.svg" width="40" height="40" />
    </a>
  </div>
</template>

<style scoped>
aside {
  min-height: 100vh;
}

nav {
  display: flex;
  justify-content: center;
  width: 100%;
  font-size: 1rem;
  text-align: center;
  margin-top: 2rem;
  padding: 1rem 0;
  margin: auto;
}

nav a.router-link-exact-active {
  color: var(--color-text);
}

nav a.router-link-exact-active:hover {
  background-color: transparent;
}

nav a {
  display: flex;
  padding: 0.5rem 1rem;
  border-left: 1px solid var(--color-border);
  border-right: 1px solid var(--color-border);
}

.material-icons {
  margin-right: 0.5rem;
}

h1 {
  font-weight: 500;
  font-size: 2.6rem;
  top: -10px;
}

h3 {
  font-size: 1.2rem;
}

.greetings h1,
.greetings h3 {
  text-align: center;
}

.social-media {
  margin: auto;
  display: flex;
  justify-content: center;
}

.social-media a {
  align-content: center;
  align-items: center;
  padding: 0.43rem;
  width: 56px;
  height: 56px;
  margin: 8px;
  border: 2px solid #fff;
  border-radius: 50%;
  filter: brightness(0) saturate(100%) invert(17%) sepia(52%) saturate(6251%) hue-rotate(277deg) brightness(75%) contrast(130%);
}

.social-media a:hover {
  background-color: hsla(280, 100%, 60%, 0.2);
  filter: brightness(0) saturate(100%) invert(37%) sepia(87%) saturate(3380%) hue-rotate(259deg) brightness(93%) contrast(123%);
}
</style>
