<template lang="pug">
  div
    h1 feathericon
    p v{{version}}
</template>

<script>
import { version } from 'feathericon/package.json';

export default {
  data: function() {
    return {
      version: version
    }
  }
}
</script>

<style lang="css">
</style>
