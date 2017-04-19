<template>
  <div>
    Count is {{ count }} aaaabbbbcc
  </div>
</template>

<script>
import store from '../store/'

export default {
  data () {
    return { }
  },
  computed: {
    count () {
      return store.state.counter
    }
  }
}
</script>
<style>
</style>
