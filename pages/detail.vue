<template>
  <div>
    <section id="hero-detail" class="section-bg-colored">
        <h1>CTO / Co-Founder, Drinkeasy</h1>
        <p><em>NYC, Berlin</em></p>
        <p>A chatbot-fueled eCommerce platform for craft spirits. Techstars 2017</p>
        <a href="drinkeasy.co">drinkeasy.co</a>
    </section>
    <section class="grid section-bg-plain">
        <div class="info-about-the-project">
            <h2>Subtitle One</h2>
            <p>Wie oder wo genau die Mathematik entstand, kann man heute nicht mehr sagen. Fakt ist aber, dass man schon vor circa 5000 Jahren damit angefangen hat. Zuerst waren da die Babylonier. Sie waren die ersten Menschen, die eine Form der Mathematik benutzten, um ihre Anzahl an Vieh zu zählen. Ungefähr 2000 Jahre später entwickelten die Ägypter erste Formeln. Ähnlich wie bei den Babyloniern handelte es sich hier um die Berechnungen um Bauwerke zu errichten. Allerdings handelte es sich hier auch um Pyramiden. Auf Papyrusrollen lösten sie sogar schon richtige mathematische Aufgaben, die sie sich selbst stellten.
            </p>
            <h2>Subtitle Two</h2>
            <p>Wie oder wo genau die Mathematik entstand, kann man heute nicht mehr sagen. Fakt ist aber, dass man schon vor circa 5000 Jahren damit angefangen hat. Zuerst waren da die Babylonier. Sie waren die ersten Menschen, die eine Form der Mathematik benutzten, um ihre Anzahl an Vieh zu zählen. Ungefähr 2000 Jahre später entwickelten die Ägypter erste Formeln. Ähnlich wie bei den Babyloniern handelte es sich hier um die Berechnungen um Bauwerke zu errichten. Allerdings handelte es sich hier auch um Pyramiden. Auf Papyrusrollen lösten sie sogar schon richtige mathematische Aufgaben, die sie sich selbst stellten.
            </p>
            <h2>Subtitle Three</h2>
            <p>Wie oder wo genau die Mathematik entstand, kann man heute nicht mehr sagen. Fakt ist aber, dass man schon vor circa 5000 Jahren damit angefangen hat. Zuerst waren da die Babylonier. Sie waren die ersten Menschen, die eine Form der Mathematik benutzten, um ihre Anzahl an Vieh zu zählen. Ungefähr 2000 Jahre später entwickelten die Ägypter erste Formeln. Ähnlich wie bei den Babyloniern handelte es sich hier um die Berechnungen um Bauwerke zu errichten. Allerdings handelte es sich hier auch um Pyramiden. Auf Papyrusrollen lösten sie sogar schon richtige mathematische Aufgaben, die sie sich selbst stellten.
            </p>
        </div>
        <div class="logo">
            <img src="../assets/drink-easy-logo.png" alt="drink-easy">
        </div>
    </section>
    <section id="contact" class="section-bg-colored">
      <h2>Get in Touch</h2>
      <p>nicholas.manning at gmail dot com</p>
      <p><a href="https://www.twitter.com/seenickcode" target="_blank">@seenickcode</a></p>
      <p><a href="https://www.linkedin.com/in/nicholasmanning" target="_blank">LinkedIn Profile</a></p>
    </section>
  </div>
</template>

<script>
</script>

<style>
    #hero-detail {
        padding-right: 30px;
    }
    .grid {
        display: grid;
        grid-template-columns: 4fr 1fr;
    }
    img {
        width: 200px;
        margin-top: 0px;
        margin-left: 10%;
    }
    .section-bg-colored {
        color: #ffffff;
    }
    @media screen and (max-width: 700px) {
        .grid {
            padding-right: 10%;
            grid-template-columns: 1fr;
        }
        .logo img {
            display: none;
        }
    }
</style>
