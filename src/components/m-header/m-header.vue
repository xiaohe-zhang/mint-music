<template>
  <div class="m-header">
    <h1 class="text">薄荷音乐吧</h1>
  </div>
</template>

<style lang="stylus" scoped>
  @import "~common/stylus/variable"
  @import "~common/stylus/mixin"
  .m-header
    position: relative
    height: 44px
    text-align :center
    color: $color-theme
    font-size : 0
    .text
      display: inline-block
      font-size: $font-size-large
      vertical-align :top
      line-height: 44px
</style>
