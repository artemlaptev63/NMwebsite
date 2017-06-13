<template>
  <div>
    <section class="section-bg-colored hero">
        <h1>CTO / Co-Founder, Drinkeasy</h1>
        <p><em>NYC, Berlin</em></p>
        <p>A chatbot-fueled eCommerce platform for craft spirits. Techstars 2017</p>
        <a href="#">drinkeasy.co</a>
    </section>
    <div class="grid">
        <section class="section-bg-plain">
            <h2>Subtitle One</h2>
            <p>Wie oder wo genau die Mathematik entstand, kann man heute nicht mehr sagen. Fakt ist aber, dass man schon vor circa 5000 Jahren damit angefangen hat. Zuerst waren da die Babylonier. Sie waren die ersten Menschen, die eine Form der Mathematik benutzten, um ihre Anzahl an Vieh zu zählen. Ungefähr 2000 Jahre später entwickelten die Ägypter erste Formeln. Ähnlich wie bei den Babyloniern handelte es sich hier um die Berechnungen um Bauwerke zu errichten. Allerdings handelte es sich hier auch um Pyramiden. Auf Papyrusrollen lösten sie sogar schon richtige mathematische Aufgaben, die sie sich selbst stellten.
            </p>
            <h2>Subtitle Two</h2>
            <p>Wie oder wo genau die Mathematik entstand, kann man heute nicht mehr sagen. Fakt ist aber, dass man schon vor circa 5000 Jahren damit angefangen hat. Zuerst waren da die Babylonier. Sie waren die ersten Menschen, die eine Form der Mathematik benutzten, um ihre Anzahl an Vieh zu zählen. Ungefähr 2000 Jahre später entwickelten die Ägypter erste Formeln. Ähnlich wie bei den Babyloniern handelte es sich hier um die Berechnungen um Bauwerke zu errichten. Allerdings handelte es sich hier auch um Pyramiden. Auf Papyrusrollen lösten sie sogar schon richtige mathematische Aufgaben, die sie sich selbst stellten.
            </p>
            <h2>Subtitle Three</h2>
            <p>Wie oder wo genau die Mathematik entstand, kann man heute nicht mehr sagen. Fakt ist aber, dass man schon vor circa 5000 Jahren damit angefangen hat. Zuerst waren da die Babylonier. Sie waren die ersten Menschen, die eine Form der Mathematik benutzten, um ihre Anzahl an Vieh zu zählen. Ungefähr 2000 Jahre später entwickelten die Ägypter erste Formeln. Ähnlich wie bei den Babyloniern handelte es sich hier um die Berechnungen um Bauwerke zu errichten. Allerdings handelte es sich hier auch um Pyramiden. Auf Papyrusrollen lösten sie sogar schon richtige mathematische Aufgaben, die sie sich selbst stellten.
            </p>
        </section>
        <section class="drink-easy-logo">
            <img src="../assets/drink-easy-logo.png" alt="drink-easy">
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
</script>

<style>
    .grid {
        display: grid;
        grid-template-columns: 4fr 1fr;
    }
    .drink-easy-logo img {
        width: 60%;
        margin-top: 120px;
        margin-left: 10%;
    }
    .section-bg-colored {
        color: #ffffff;
    }
    @media screen and (max-width: 400px) {
        .grid {
            padding-right: 10%;
            grid-template-columns: 1fr;
        }
        .drink-easy-logo {
            grid-area: 1 / 1;
        }
        .drink-easy-logo img {
            padding-left: 10%;
        }
    }
</style>
