<template>
  <div class="default-wrapper">
    <the-header/>
    <nuxt/>
    <the-footer/>
  </div>
</template>

<script>
import TheHeader from '@/components/TheHeader.vue'
import TheFooter from '@/components/TheFooter.vue'

export default {
  components: {
    TheHeader,
    TheFooter
  }
}
</script>

<style>
html {
  font-family: 'Futura', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto,
    'Helvetica Neue', Arial, sans-serif;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
  background: rgb(237, 237, 237);
}

*,
*:before,
*:after {
  box-sizing: border-box;
  margin: 0;
}

.default-wrapper {
  max-width: 1440px;
  margin: 0 auto;
  background-color: #fff;
}

img {
  display: block;
}
</style>
