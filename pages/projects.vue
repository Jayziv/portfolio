<!-- pages/projects.vue -->

<template>
  <section class="section is-medium">
    <div class="container has-text-centered">
      <h1 class="title">My Projects</h1>

      <p>This portfolio is my first project built with <span style="color:#41B883;font-weight:bold;">Vue</span>, <span style="color:#35495E;font-weight:bold;">Nuxt</span> and <span style="color:#00D1B2;font-weight:bold;">Bulma</span>.</p>
      
      <p>My current focus is creating <nuxt-link class="project-links" to="/modular-cards">modular cards</nuxt-link> of an e-commerce site.
      <br>
      <br>
      <p>Here is a list for my own purposes of things I want to have a nosey at for my own understanding</p>
      <br>
      <ul class="project-list">
          <li><span class="project-point">API Integration</span> - Possibly look at doing something with Dungeons & Dragons spell lists as a practical project.</li>
          <li><span class="project-point">Look at product database info storage</span> - How to integrate with nuxt and look at system for easily creating a product 'object'&nbsp;or&nbsp;so.</li>
          <li><span class="project-point">Search</span> - Look at searching list of products or objects.</li>
          <li><span class="project-point">Payment Systems</span> - Look at SWIFT, look for alternative solutions, weigh pro's and con's.</li>
          <li><span class="project-point">Security</span> - More than likely walks hand in hand with above.</li>
      </ul>
          
      <p>
        Most of my Stuff can be found on <a href="https://github.com/Jayziv" target="_blank">GitHub</a>.
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
.project-point{font-weight:bold;}
.project-list{
  line-height:1.5;
}


</style>
