<template>
  <div>
    <sample-component :title="indextitle">
      <div class="come">
        slot 1117
      </div>
    </sample-component>
    <nuxt-link to="/about">ABOUT</nuxt-link>
  </div>
</template>

<script>
import SampleComponent from '~/components/SampleComponent.vue'

export default {
  components: {
    SampleComponent
  },
  data() {
    return {
      indextitle: 'Nuxt.js data'
    }
  }
}
</script>
