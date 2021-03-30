<template>
<div id="app">
    <h1>黑马</h1>
    <router-view></router-view>
    <i class="iconfont icon-fenxiang"></i>
    <van-button type="primary">主要按钮</van-button>
<van-button type="info">信息按钮</van-button>
<van-button type="default">默认按钮</van-button>
<van-button type="warning">警告按钮</van-button>
<van-button type="danger">危险按钮</van-button>
</div>
</template>

<script>
export default {
  name: 'App',
  data () {
    return {

    }
  },
  methods: {

  },
  computed: {

  }
}
</script>

<style scoped>

</style>
