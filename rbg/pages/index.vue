<template>
  <div class="container">
    <div>
      <logo />
      <h1 class="title">
        rbg
      </h1>
      <h2 class="subtitle">
        My spectacular Nuxt.js project
      </h2>
      <div class="links">

        <a
          href="https://github.com/nuxt/nuxt.js"
          target="_blank"
          class="button--grey"
        >
          GitHub
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

