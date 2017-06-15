<template>
  <div>
    <section class="section-bg-colored hero">
      <h1>Nicholas Manning</h1>
      <ul>
        <li>Technical CTO<li>
        <li>Software Craftsman</li>
        <li>Berlin &amp; NYC</li>
      </ul>
    </section>
    <section id="experience" class="section-bg-plain section-spacing-indented">
      <h2>In a Nutshell</h2>
      <ul>
        <li>Builder and Manager of Technical Teams</li>
        <li>7+ year in leadership roles, 15+ years of software engineering experience</li>
        <li>Specializing in Bot, Mobile and eCommerce Product Strategy</li>
      </ul>
    </section>
    <section id="technologies" class="section-bg-colored">
      <h2>Skills</h2>
      <ul>
        <li><b>Management:</b>&nbsp; Product Strategy, Technical Team Management</li>
        <li><b>Languages:</b>&nbsp; Golang, JavaScript, ES6, Swift, Objective-C, Elixir, Ruby, C#, Java</li>
        <li><b>Frameworks:</b>&nbsp; Vue, Nuxt, React Native, React, Phoenix, .NET, Ruby on Rails, Node.js</li>
        <li><b>Infrastructure:</b>&nbsp; AWS, Nginx, Docker, Ansible, Terraform</li>
        <li><b>Specializations:</b>&nbsp; Bots, Mobile, eCommerce, Conversational Commerce</li>
      </ul>
      <h2>Clients</h2>
      <img src="../assets/adidas-logo.png" alt="adidas">
      <img src="../assets/benefit-logo.png" alt="benefit"><br/>
      <img src="../assets/taylormade-ogo.png" alt="taylormade">
      <img src="../assets/reebok-logo.png" alt="reebok">
    </section>
    <div class="grid">
      <section class="section-bg-plain section-spacing-indented">
        <h2>Current</h2>
        <h3>CTO / Co-Founder, Drinkeasy</h3>
        <p><em>NYC, Berlin</em></p>
        <p>A chatbot-fueled eCommerce platform for craft spirits.<br/>
           Techstars 2017</p>
        <a href="http://www.drinkeasy.co" target="_blank">drinkeasy.co</a>
      </section>
      <section class="drink-easy-logo">
        <router-link to="/detail"><img src="../assets/drink-easy-logo.png" alt="drink-easy"></router-link>
      </section>
      <section class="section-bg-plain section-spacing-indented">
        <h2>Previous</h2>
        <h3>CTO / Co-Founder, Swig</h3>
        <p><em>NYC</em></p>
        <p>Photosharing for the world's taste explorers.</p>
        <a href="http://www.swig.co" target="_blank">swig.co</a>
      </section>
      <section class="swig-logo">
        <router-link to="/detail"><img src="../assets/swig-logo.png" alt="swig-logo"></router-link>
      </section>
    </div>
    <section class="section-bg-colored contact">
      <h2>Get in Touch</h2>
      <p>nicholas.manning at gmail dot com</p>
      <p><a href="https://www.twitter.com/seenickcode" target="_blank">@seenickcode</a></p>
      <p><a href="https://www.linkedin.com/in/nicholasmanning" target="_blank">linkedin.com/in/nicholasmanning</a></p>
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
.grid {
    display: grid;
    grid-template-columns: 3fr 1fr;
}
.swig-logo,
.drink-easy-logo {
    align-self: center;
    justify-self: end;
}
.drink-easy-logo img,
.swig-logo img {
    width: 50%;
}
.grid .section-bg-plain {
    padding-left: 40%;
}
.grid .section-bg-plain p:nth-of-type(1) {
    margin-top: 0px;
}
.grid h3 {
    margin-bottom: 0px;
}
/*grid*/
@media screen and (max-width: 400px) {
  #experience {
    padding-right: 30px;
  }
  img {
      width: 50%;
      display: block;
  }
  .grid {
    grid-template-columns: 1fr;
    padding-right: 30px;
  }
  .grid h2 {
    margin-top: -30px;
  }
  .drink-easy-logo {
    grid-row: 1 / 2;
  }
  .swig-logo {
    grid-row: 3 / 4;
  }
  .grid .section-bg-plain {
    padding-left: 20%;
  }
  .drink-easy-logo img {
    padding-left: 19%;
  }
  .swig-logo {
    padding-left: 20%;
  }
  .drink-easy-logo img,
  .swig-logo img {
    width: 40%;
  }
}
</style>
