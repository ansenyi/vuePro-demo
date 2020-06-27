<template>
  <div>
    vant练习
    <van-button type="default">默认按钮</van-button>
    <van-button type="primary">主要按钮</van-button>
    <van-button type="info">信息按钮</van-button>
    <van-button type="warning">警告按钮</van-button>
    <van-button type="danger">危险按钮</van-button>
  </div>
</template>
<script>
//引入页面数据

export default {
  data() {
    return {
      data: {},
      items: []
    };
  },
  methods: {
    loginOut() {}
  }
};
</script>
