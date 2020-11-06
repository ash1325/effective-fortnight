<template>
  <nuxt-link to="/">TOP</nuxt-link>
</template>

<script>
export default {
  head(){
    return {
      title: 'About',
      meta: [
        { hid: 'description', name: 'description', content: 'About ページ' }
      ]
    }
  },
  layout: 'darkmode'
}
</script>

<style lang="scss">

</style>
