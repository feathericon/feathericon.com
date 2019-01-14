<template lang="pug">
  div
    h1 {{ description }}
</template>

<script>
import { description, author } from 'feathericon/package.json';

export default {
  layout: 'app',
  data: function() {
    return {
      description: description
    }
  },
  head () {
    return {
      title: 'feathericon'
    }
  }
}
</script>
