<template>
  <div class="header">
    <div class="header-left">
      <div class="iconfont back-icon">&#xe624;</div>
    </div>
    <div class="header-input">
      <span class="iconfont">&#xe632;</span>
      输入城市/景点/游玩主题
    </div>
    <div class="header-right">
      城市
      <span class="iconfont arrow-icon">&#xe6aa;</span>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Header'
}
</script>

<style lang="stylus" scoped>
  @import '~@/assets/styles/varibles.styl'
  .header
    display: flex
    line-height: .86rem
    background-color: $bgColor
    color: #ffffff
    .header-left
      width: .64rem
      /*float: left*/
      .back-icon
          /*margin: 0 auto*/
          text-align center
          font-size:.4rem
    .header-input
      flex:1
      margin: .12rem .2rem
      padding-left :.2rem
      background :#ffffff
      border-radius: .1rem
      color: #cccccc
      height:.64rem
      line-height: .64rem
    .header-right
      width: 1.24rem
      /*float: right*/
      text-align: center
      .arrow-icon
        font-size .24rem
        margin-left:-2px
</style>
