<template>
    <h1>Details: {{ slug }}</h1>
</template>
  
<script>
export default {
    name: 'RangerEvents',
    async asyncData({ params }) {
      const slug = params.slug // When calling /abc the slug will be "abc"
      return { slug }
    }
}
</script>
