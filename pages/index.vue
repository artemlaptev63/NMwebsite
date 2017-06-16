<template>
  <div>
    <section id="hero" class="section-bg-colored">
      <h1>Nicholas Manning</h1>
      <ul>
        <li>Technical CTO<li>
        <li>Software Craftsman</li>
        <li>Berlin Based New Yorker</li>
      </ul>
    </section>
    <section id="experience" class="section-bg-plain">
      <h2>In a Nutshell</h2>
      <ul>
        <li>Builder and Manager of Technical Teams</li>
        <li>7+ year in leadership roles, 15+ years of software engineering experience</li>
        <li>Specializing in Bot, Mobile and eCommerce Product Strategy</li>
      </ul>
    </section>
    <section id="technologies" class="section-bg-colored">
      <div class="skills">
      <h2>Skills</h2>
        <ul>
          <li><b>Management:</b>&nbsp; Product Strategy, Technical Team Management</li>
          <li><b>Languages:</b>&nbsp; Golang, JavaScript, ES6, Swift, Objective-C, Elixir, Ruby, C#, Java</li>
          <li><b>Frameworks:</b>&nbsp; Vue, Nuxt, React Native, React, Phoenix, .NET, Ruby on Rails, Node.js</li>
          <li><b>Infrastructure:</b>&nbsp; AWS, Nginx, Docker, Ansible, Terraform</li>
          <li><b>Specializations:</b>&nbsp; Bots, Mobile, eCommerce, Conversational Commerce</li>
        </ul>
      </div>
      <div class="clients">
        <h2>Clients</h2>
        <img src="../assets/adidas-logo.png" alt="adidas">
        <img src="../assets/benefit-logo.png" alt="benefit"><br/>
        <img src="../assets/taylormade-ogo.png" alt="taylormade">
        <img src="../assets/reebok-logo.png" alt="reebok">
      </div>
    </section>
    <section class="section-bg-plain">
      <div class="job-item">
        <div class="detail">
          <h2>Current</h2>
          <h3>CTO / Co-Founder, Drinkeasy</h3>
          <p class="city"><em>NYC, Berlin</em></p>
          <p>A chatbot-fueled eCommerce platform for craft spirits.<br/>
             Techstars 2017</p>
          <a href="http://www.drinkeasy.co" target="_blank">drinkeasy.co</a>
        </div>
        <div class="job-logo-cell">
          <router-link to="/detail"><img src="../assets/drink-easy-logo.png" alt="drink-easy"></router-link>
        </div>
      </div>
      <div class="job-item">
        <div class="detail">
          <h2>Previous</h2>
          <h3>CTO / Co-Founder, Swig</h3>
          <p class="city"><em>NYC</em></p>
          <p>Photosharing for the world's taste explorers.</p>
          <a href="http://www.swig.co" target="_blank">swig.co</a>
        </div>
        <div class="job-logo-cell">
          <router-link to="/detail"><img src="../assets/swig-logo.png" alt="swig-logo"></router-link>
        </div>
      </div>
    </section>
    <section id="contact" class="section-bg-colored">
      <h2>Get in Touch</h2>
      <p>nicholas.manning at gmail dot com</p>
      <p><a href="https://www.twitter.com/seenickcode" target="_blank">@seenickcode</a></p>
      <p><a href="https://www.linkedin.com/in/nicholasmanning" target="_blank">linkedin.com</a></p>
    </section>
  </div>
</template>

<script>
import Job from '~components/job.vue'

export default {
  components: {
    Job
  }
}
</script>

<style>
/*grid*/
.job-item {
  display: grid;
  grid-template-columns: 1fr 1fr;
  grid-gap: 100px;
  margin-bottom: 50px;
}
.job-logo-cell {
  align-self: center;
  justify-self: center;
}
.job-logo-cell img {
  width: 150px;
}
.detail h3 {
  margin-bottom: 0px;
}
.city {
  margin-top: 0px;
}
/*grid*/
@media screen and (max-width: 600px) {
  .job-item {
    display: grid;
    grid-template-columns: 1fr;
  }
  .job-item img {
    display: none;
  }
}
@media screen and (max-width: 400px) {
  #experience {
    padding-right: 30px;
  }
  img {
    display: block;
  }
  br {
    display: none;
  }
}
</style>
