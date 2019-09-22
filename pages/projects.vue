<!-- pages/projects.vue -->

<template>
  <section class="section is-medium">
    <div class="container has-text-centered">
      <h1 class="title">My Projects</h1>

      <p>This portfolio is my first project built with <span style="color:#41B883;font-weight:bold;">Vue</span>, <span style="color:#35495E;font-weight:bold;">Nuxt</span> and <span style="color:#00D1B2;font-weight:bold;">Bulma</span>.</p>
      
      <p>My current focus is creating modular sections of an e-commerce site.
      <br>
      <p>
        Some of my projects can be found on <a href="https://github.com/Jayziv" target="_blank">GitHub</a>.
      </p>
    </div>
  </section>
</template>

<style>
.msg {
    transition: all .3s ease;
    height: 30px;
    padding: 10px;
    background-color: #eee;
    overflow: hidden;
}
.msg.v-enter, .msg.v-leave {
    height: 0;
    padding: 0 10px;
    opacity: 0;
}
</style>
