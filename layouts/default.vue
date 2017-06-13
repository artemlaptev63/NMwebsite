<template>
  <div>
    <nuxt/>
  </div>
</template>

<style>
body {
    margin: 0px;
    font-family: "Avenir", sans-serif;
}
.hero {
    background-image: url("~assets/rectangle-1.png");
}
#technologies {
    background-image: url("~assets/rectangle-2.png");
}
.contact {
    background-image: url("~assets/rectangle-3.png");
}
.hero, #technologies, .contact {
    background-repeat: no-repeat;
    background-size: 100% 100%;
}
h1 {
    margin-top: 0px;
    font-size: 35px;
    font-weight: bold;
    letter-spacing: 0.5px;
    color: #ffffff;
}
.section-bg-colored {
    padding: 15% 0% 17% 20%;
}
ul {
    list-style: none;
    padding-left: 0px;
    color: #ffffff;
    font-size: 20px;
    line-height: 1.5;
    letter-spacing: 0.5px;
    font-weight: 100;
}
.section-bg-plain {
    padding: 10% 0% 10% 30%;
}
h2 {
    font-size: 35px;
    font-weight: bold;
    letter-spacing: 0.5px;
    color: #000000;
}
a {
    text-decoration: none;
    color: #53a0fe;
    font-size: 20px;
}
p {
    font-size: 20px;
    line-height: 1.5;
    letter-spacing: 0.5px;
}
.section-bg-plain ul {
    color: #000000;
}
#technologies h2, .contact h2, .contact {
    color: #ffffff;
}
#technologies ul {
    display: inline-block;
}
#technologies ul:nth-of-type(2),
#technologies ul:nth-of-type(3) {
    padding-left: 12%;
}
#technologies h2:nth-of-type(2) {
    margin-top: 80px;
}
img {
    width: 15%;
}
#technologies img:nth-of-type(2),
#technologies img:nth-of-type(4) {
    padding-left: 13%;
}
#technologies img:nth-of-type(3),
#technologies img:nth-of-type(4) {
    padding-top: 30px;
    padding-bottom: 20px;
}
.contact {
    padding-bottom: 5%;
}
/*for mobile*/
@media screen and (max-width: 400px) {
    #technologies ul {
      display: block;
    }
    #technologies ul:nth-of-type(2),
    #technologies ul:nth-of-type(3) {
      padding-left: 0%;
      margin-top: 0px;
      margin-bottom: 0px;
    }
    #technologies ul:nth-of-type(1) {
      margin-bottom: 0px;
    }
    .section-bg-plain {
      padding: 15% 0% 17% 20%;
    }
    #experience li {
      margin-top: 30px;
    }
    #technologies img:nth-of-type(2),
    #technologies img:nth-of-type(4) {
      padding-left: 0%;
    }
    #technologies img:nth-of-type(1),
    #technologies img:nth-of-type(2),
    #technologies img:nth-of-type(3),
    #technologies img:nth-of-type(4) {
      padding-top: 30px;
      padding-bottom: 50px;
    }
    #technologies img:nth-of-type(4) {
      padding-bottom: 80px;
    }
    #technologies h2:nth-of-type(1) {
      margin-top: 60px;
    }
    .contact p {
      font-size: 18px;
    }
    body p,
    body ul {
      font-size: 18px;
    }
}
  /*for mobile*/
</style>
