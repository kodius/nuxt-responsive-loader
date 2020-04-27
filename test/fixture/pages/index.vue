<template>
  <figure class="picture">
    <picture>
      <source :srcset="require('~/assets/nuxt.jpg').srcSetWebP" type="image/webp" />
      <source :srcset="require('~/assets/nuxt.jpg').srcSet" type="image/jpeg" />
      <img src="~/assets/nuxt.jpg" />
    </picture>
  </figure>
</template>

<script>
export default {
  loading: false
}
</script>
