<template>
  <div class="header">
    <div class="header-left">
      <span class="iconfont back-icon">&#xe624;</span>
    </div>
    <div class="header-input">
      <span class="iconfont">&#xe632;</span>
      输入城市/景点/游玩主题</div>
    <div class="header-right">
      城市
      <span class="iconfont down-icon">&#xe64a;</span>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HomeHeader'
}
</script>

<style lang="stylus" scoped>
  .header
    display: flex
    line-height: .86rem
    background: #00bcd4
    color: #fff
    .header-left
      width: .64rem
      float: left
      .back-icon
        text-align: center
        font-size: .4rem
    .header-input
      height: .64rem
      color: #ccc
      line-height: .64rem
      margin-top: .12rem
      margin-left: .2rem
      flex: 1
      background: #ffffff
      border-radius: .1rem
    .header-right
      width: 1.24rem
      float: right
      text-align: center
      .down-icon
        font-size: .2rem
        margin-left: -.04rem
</style>
