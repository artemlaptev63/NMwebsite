<template>
  <div>
    <section id="hero">
      <h1>Nick Manning</h1>
      <ul>
        <li>CTO Consultant</li>
        <li>Startup hacker</li>
        <li>Berlin based New Yorker</li>
      </ul>
    </section>
    <section>
      <h2>Experience</h2>
      <ul>
        <li>7 years in CTO &amp; Technical Leadership Roles</li>
        <li>13 years of Software Architecture &amp; Development</li>
        <li>5 years of Mobile and eCommerce Product Strategy Consulting</li>
      </ul>
    </section>
    <section>
      <h2>Technologies</h2>
      <ul>
        <li>Technology 1</li>
        <li>Technology 2</li>
        <li>Technology 3</li>
      </ul>
      <ul>
        <li>Technology 4</li>
        <li>Technology 5</li>
        <li>Technology 6</li>
      </ul>
      <ul>
        <li>Technology 7</li>
        <li>Technology 8</li>
        <li>Technology 9</li>
      </ul>
      <h2>Featured Clients</h2>
      <img src="../assets/adidas-logo.png" alt="adidas">
      <img src="../assets/benefit-logo.png" alt="benefit">
      <img src="../assets/taylormade-ogo.png" alt="taylormade">
      <img src="../assets/reebok-logo.png" alt="reebok">
    </section>
    <section>
      <h2>Current</h2>
      <h3>CTO / Co-Founder, Drinkeasy</h3>
      <p><em>NYC, Berlin</em></p>
      <p>A chatbot-fueled eCommerce platform for craft spirits.<br/>
         Techstars 2017</p>
      <a href="drinkeasy.co">drinkeasy.co</a>
      <img src="../assets/drink-easy-logo.png" alt="drink-easy">
    </section>
    <section>
      <h2>Recent</h2>
      <h3>CTO / Co-Founder, Swig</h3>
      <p><em>NYC</em></p>
      <p>Photosharing for the world's drink explorers.</p>
      <a href="swig.co">swig.co</a>
      <img src="../assets/swig-logo.png" alt="swig-logo">
    </section>
    <section>
      <h2>Get in Touch</h2>
      <p>0123456789</p>
      <p>nicholas.manning@gmail.com</p>
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
section#hero {
  min-height: 800px;
  background-image: url("~assets/rectangle-1.png");
  background-repeat: no-repeat;
  background-size: contain;
}
</style>
