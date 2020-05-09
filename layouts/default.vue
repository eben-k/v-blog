<template>
  <div>
    <top-header />
    <main>
      <nuxt />
    </main>
    <bottom-footer />
  </div>
</template>
<script lang="ts">
import Vue from 'vue'
import TopHeader from '~/components/TopHeader.vue'
import BottomFooter from '~/components/BottomFooter.vue'

export default Vue.extend({
  components: {
    TopHeader,
    BottomFooter
  }
})
</script>

<style lang="scss">
@import '../assets/scss/styles.scss';
</style>
