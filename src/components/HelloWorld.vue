<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
  name: 'HelloWorld',
  props: {
    msg: {
      type: String,
      default: '',
    },
  },
})
</script>

<style scoped lang="scss"></style>
