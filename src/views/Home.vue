<template>
  <div class="home">
    home
  </div>
</template>

<script>

export default {
  name: 'Home',
  created() {
    console.log(this.$store)
    /*
    commit: ƒ boundCommit(type, payload, options)
    dispatch: ƒ boundDispatch(type, payload)
    getters: {}
    strict: false
    */
  }
}
</script>

