<template>
<div class="app-wrapper">
  <Body />
  <Footer />
</div>
</template>

<script>

import Body from './components/Body.vue'
import Footer from './components/common/Footer.vue'


export default {
  name: 'App',
  components: {
   Body
    , Footer
  }
}
</script>
