<template>
  <div class="hello">
    <img-inputer
      v-model="file"
      theme="light"
      size="large"
      class="img-container"
    />
  </div>
</template>

<script>
export default {
  data() {
    return {
      file: ''
    }
  }
}
</script>

<style lang="stylus">
.img-container
  .img-inputer__preview-img
    width auto
    max-width 100%
    max-height 100%
</style>
