<template>
  <view class="index" style="filter: grayscale(1)">
    <!-- 上方这个style不会最终输出 -->
    <text>{{ msg }}</text>
  </view>
</template>

<script>
import './index.css'

export default {
  data () {
    return {
      msg: 'Hello world!'
    }
  }
}
</script>
