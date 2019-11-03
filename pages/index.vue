<template>
  <div class="container">
    <div>

      <h1 class="title">
        tegehoge-camp Vol2
      </h1>
      <h2 class="subtitle">
        We are Developer in Miyazaki
      </h2>
      <div class="links">
        <a
          href="https://tege.work/"
          target="_blank"
          class="button--green"
        >
          Tegehoge Official Web
        </a>
        <a
          href="https://tegehoge.connpass.com"
          target="_blank"
          class="button--grey"
        >
          tegehoge connpass
        </a>
      </div>
    </div>
  </div>
</template>

<script>
import Logo from '~/components/Logo.vue'

export default {
  components: {
    Logo
  }
}
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: green;
  letter-spacing: 1px;
  padding-bottom: 35px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
