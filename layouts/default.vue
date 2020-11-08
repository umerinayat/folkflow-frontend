<template>
  <div>
     <Horizontal>
      <slot />
    </Horizontal>
    <nuxt />
  </div>
</template>

<script>

import Horizontal from "./horizontal";

export default {
  components: {
    Horizontal
  }
}
</script>

<style>
  
</style>
