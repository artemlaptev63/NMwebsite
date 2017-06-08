<template>
  <div>
    <section class="container">
      <h1>Nick Manning</h1>
      <p>CTO Consultant. Startup hacker. Berlin based New Yorker.</p>
      <p><a href="http://www.linkedin.com/in/nicholasmanning">linkedin.com/in/nicholasmanning</a></p>
      <job />
      <job />
      <job />
      <nuxt-link to="/detail">Detail</nuxt-link>
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

</style>
