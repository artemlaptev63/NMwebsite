<template>
  <div>
    <section id="hero-detail" class="section-bg-colored">
        <h1>CTO / Co-Founder, Drinkeasy</h1>
        <p><em>NYC, Berlin</em></p>
        <p>A chatbot-fueled eCommerce<br/>
           platform for craft spirits.<br/> Techstars 2017</p>
        <a href="drinkeasy.co">drinkeasy.co</a>
    </section>
    <!-- <section id="hero-detail-image" class="">
        <img src="../assets/drinkeasy-hero-image.png">
    </section> -->
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
            <!-- <h2>Visit the site:</h2> -->
            <a href="drinkeasy.co">drinkeasy.co</a>
        </div>
        <!-- disabling this because it looks quite strange here on the right -->
        <!-- <div class="logo">
            <img src="../assets/drinkeasy-logo.png" alt="drinkeasy">
        </div> -->
    </section>
    <section id="contact" class="section-bg-colored">
        <a href="https://www.linkedin.com/in/nicholasmanning" target="_blank"><img src="../assets/linkedin-logo.png" alt="linkedin-logo"></a>
        <a href="https://twitter.com/seenickcode" target="_blank"><img src="../assets/twitter-logo.png" alt="twitter-logo"></a>
        <a href="https://medium.com/@seenickcode" target="_blank"><img src="../assets/medium-logo.png" alt="medium-logo"></a>
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
    #contact img {
        width: 150px;
        margin-top: 25px;
        margin-left: 10%;
    }
    #contact img {
        margin-left: 0%;
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
