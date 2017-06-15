<template>
  <div>
    <section class="section-bg-colored hero">
      <h1>Nick Manning</h1>
      <ul>
        <li>CTO Consultant</li>
        <li>Startup hacker</li>
        <li>Berlin based New Yorker</li>
      </ul>
    </section>
    <section id="experience" class="section-bg-plain section-spacing-indented">
      <h2>Experience</h2>
      <ul>
        <li>7 years in CTO &amp; Technical Leadership Roles</li>
        <li>13 years of Software Architecture &amp; Development</li>
        <li>5 years of Mobile and eCommerce Product Strategy Consulting</li>
      </ul>
    </section>
    <section id="technologies" class="section-bg-colored">
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
        <a href="drinkeasy.co">drinkeasy.co</a>
      </section>
      <section class="drink-easy-logo">
        <router-link to="/detail"><img src="../assets/drink-easy-logo.png" alt="drink-easy"></router-link>
      </section>
      <section class="section-bg-plain section-spacing-indented">
        <h2>Recent</h2>
        <h3>CTO / Co-Founder, Swig</h3>
        <p><em>NYC</em></p>
        <p>Photosharing for the world's drink explorers.</p>
        <a href="swig.co">swig.co</a>
      </section>
      <section class="swig-logo">
        <router-link to="/detail"><img src="../assets/swig-logo.png" alt="swig-logo"></router-link>
      </section>
    </div>
    <section class="section-bg-colored contact">
      <h2>Get in Touch</h2>
      <p>0123456789<br/>
         nicholas.manning@gmail.com</p>
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
