<template>
  <div v-show="showFlag" class="food">

  </div>
</template>
<script type="text/ecmascript-6">
  export default {
    props:{
      food:{
        type: Object
      }
    }
  }
</script>
<style lang="stylus" rel="stylesheet/stylus">
  .food
    position fixed
    left 0
    top 48px
    bottom 0
    z-index 30
    width 100%
    background #fff
</style>
