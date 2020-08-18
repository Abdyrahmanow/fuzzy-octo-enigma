<template>
  <v-layout>
    <h1>{{ slug.blog }}</h1>
  </v-layout>
</template>

<script>
export default {
  data() {
    return {
      slug: this.$route.params,
    }
  },
  created() {
    /* eslint-disable no-console  */
    console.log(this.$route.params)
  },
}
</script>
