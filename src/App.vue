<script>
import config from './config'
export default {
  created () {
    wx.request({
      url: config.host + '/weapp/Demo',
      success: function (res) {
        console.log(res)
      }
    })
    console.log('小程序启动了')
  }
}
</script>

<style>
</style>
