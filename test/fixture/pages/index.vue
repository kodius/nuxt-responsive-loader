<template>
  <img :srcset="require('~/assets/nuxt.jpg?webp').srcSet" />
</template>

<script>
export default {
  loading: false
}
</script>
