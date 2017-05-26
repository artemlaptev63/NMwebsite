<template>
  <div>
    <section class="container">
      <h1>Nick Manning</h1>
      <p>CTO Consultant. Startup hacker. Berlin based New Yorker.</p>
      <p><a href="http://www.linkedin.com/in/nicholasmanning">linkedin.com/in/nicholasmanning</a></p>
    </section>
  </div>
</template>

<script>
// import Logo from '~components/Logo.vue'

// export default {
//   components: {
//     Logo
//   }
// }
</script>

<style>
.container {
  min-height: 100vh;
/*  display: flex;*/
  justify-content: center;
  align-items: center;
  text-align: center;
}
h1, p {
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif; /* 1 */
  display: block;
  font-weight: 300;
  font-size: 30px;
  color: #35495e;
  letter-spacing: 1px;
}
h1 {
  margin: 70px;
  font-weight: 500;
  font-size: 50px;
}
p {
  margin: 55px;
}
a {
  text-decoration: none;
}

/*.subtitle
{
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}
.links
{
  padding-top: 15px;
}*/
</style>
