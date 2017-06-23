<template>
  <div>
    <section id="hero" class="section-bg-colored">
      <div id="social-media">
        <a href="https://www.linkedin.com/in/nicholasmanning" target="_blank"><img src="../assets/linkedin-logo.png" alt="linkedin-logo"></a>
        <a href="https://twitter.com/seenickcode" target="_blank"><img src="../assets/twitter-logo.png" alt="twitter-logo"></a>
        <a href="https://medium.com/@seenickcode" target="_blank"><img src="../assets/medium-logo.png" alt="medium-logo"></a>
      </div>
      <h1>Nicholas Manning</h1>
      <ul>
        <li>CTO<li>
        <li>Bot Craftsman</li>
        <li>Berlin Based New Yorker</li>
      </ul>
      <div id="social-media-mobile">
        <a href="https://www.linkedin.com/in/nicholasmanning" target="_blank"><img src="../assets/linkedin-logo.png" alt="linkedin-logo"></a>
        <a href="https://twitter.com/seenickcode" target="_blank"><img src="../assets/twitter-logo.png" alt="twitter-logo"></a>
        <a href="https://medium.com/@seenickcode" target="_blank"><img src="../assets/medium-logo.png" alt="medium-logo"></a>
      </div>
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
          <li><b>Non-Technical:</b>&nbsp; Product Strategy, Technical Team Management</li>
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
           <h3>Recognition:</h3>
           <p>Techstars 2017</p>
          <router-link to="/detail">Learn more about Drinkeasy</router-link>
        </div>
        <div class="logo">
          <router-link to="/detail" target="_blank"><img src="../assets/drinkeasy-logo.png" alt="drinkeasy"></router-link>
        </div>
      </div>
      <div class="job-item">
        <div class="detail">
          <h2>Previous</h2>
          <h3>CTO / Co-Founder, Swig</h3>
          <p class="city"><em>NYC</em></p>
          <p>Photosharing for the world's taste explorers.</p>
          <router-link to="/detail">Learn more about Swig</router-link>
        </div>
        <div class="logo">
          <router-link to="/detail" target="_blank"><img src="../assets/swig-logo.png" alt="swig-logo"></router-link>
        </div>
      </div>
    </section>
    <section id="contact" class="section-bg-colored">
      <a href="https://www.linkedin.com/in/nicholasmanning" target="_blank"><img src="../assets/linkedin-logo.png" alt="linkedin-logo"></a>
      <a href="https://twitter.com/seenickcode" target="_blank"><img src="../assets/twitter-logo.png" alt="twitter-logo"></a>
      <a href="https://medium.com/@seenickcode" target="_blank"><img src="../assets/medium-logo.png" alt="medium-logo"></a>
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
div#social-media-mobile {
  display: none;
}
div#social-media {
  float: right;
  margin-top: -18%;
  margin-right: -14%;
}
div#social-media img {
  width: 30px;
  padding-left: 20px;
  padding-right: 30px;
}
@media screen and (max-width: 400px) {
  div#social-media {
    display: none;
  }
  div#social-media-mobile {
    display: block;
  }
  div#social-media-mobile img {
    display: inline;
    width: 30px;
    padding: 30px 40px 30px 0px;
  }
}
/*grid*/
.job-item {
  display: grid;
  grid-template-columns: 1fr 1fr;
  grid-gap: 100px;
  margin-bottom: 50px;
}
.job-item .logo {
  align-self: center;
  justify-self: center;
}
.job-item .logo img {
  width: 150px;
}
.job-item .detail h3 {
  margin-bottom: 0px;
}
.job-item .detail p {
  margin-top: 0px;
  margin-bottom: 15px;
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
