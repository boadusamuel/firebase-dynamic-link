<template>
  <Tutorial />
</template>

<script>
export default {
  name: 'IndexPage',
  mounted () {
    console.log(this.$route.query)
  }
}
</script>
