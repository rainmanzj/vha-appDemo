<style lang="stylus">
.components_PG-tabBar
  .ui-t-b-div
    position relative
    padding 0 !important
    top rpx(-20)
    width rpx(90)
    height rpx(90) !important
    font-size rpx(20) !important
    display flex
    border-radius 50%
    z-index 20
    i
      margin auto !important
  
</style>
－－－－－－－－－－－－－－－－－－－－－－－－－－－－－－－－－－－－－－－－－－－－－
<template>
  <vha-page class="components_PG-tabBar">
    <vha-view axis="y">
      <vha-subview full="height">
        <vha-scrollview>
          
          <p class="_UI-title">类型 type：无 / 基本 / 正常 / 按钮类型</p>

          <div class="_UI-showBox">
            <vha-tabbar type="none" :followMeta="false">
              <vha-tab-item icon="fa fa-home fa-2x">主页</vha-tab-item>
              <vha-tab-item icon="fa fa-commenting fa-2x">消息</vha-tab-item>
              <vha-tab-item icon="fa fa-eye fa-2x">发现</vha-tab-item>
              <vha-tab-item icon="fa fa-user fa-2x">我的</vha-tab-item>
            </vha-tabbar>
            
            <div class="_ph-2x"></div>
            
            <vha-tabbar type="base" :followMeta="false">
              <vha-tab-item icon="fa fa-home fa-2x">主页</vha-tab-item>
              <vha-tab-item icon="fa fa-commenting fa-2x">消息</vha-tab-item>
              <vha-tab-item icon="fa fa-eye fa-2x" :value="99999" :max="99">发现</vha-tab-item>
              <vha-tab-item icon="fa fa-user fa-2x">我的</vha-tab-item>
            </vha-tabbar>
            
            <div class="_ph-2x"></div>
            
            <vha-tabbar :followMeta="false">
              <vha-tab-item icon="fa fa-home fa-2x">主页</vha-tab-item>
              <vha-tab-item icon="fa fa-commenting fa-2x">消息</vha-tab-item>
              <vha-tab-item icon="fa fa-eye fa-2x">发现</vha-tab-item>
              <vha-tab-item icon="fa fa-user fa-2x" :value="99999" :max="99" tag="+">我的</vha-tab-item>
            </vha-tabbar>
            
            <div class="_ph-2x"></div>
            
            <vha-tabbar type="base" :followMeta="false">
              <vha-tab-item type="none" icon="fa fa-home fa-2x">none</vha-tab-item>
              <vha-tab-item type="base" icon="fa fa-home fa-2x">base</vha-tab-item>
              <vha-tab-item type="normal" icon="fa fa-home fa-2x">normal</vha-tab-item>
            </vha-tabbar>
          </div>
          
          <p class="_UI-title">颜色 color：信息 & 基本</p>

          <div class="_UI-showBox">
            <vha-tabbar color="success" :followMeta="false">
              <vha-tab-item icon="fa fa-home fa-2x">主页</vha-tab-item>
              <vha-tab-item icon="fa fa-commenting fa-2x">消息</vha-tab-item>
              <vha-tab-item icon="fa fa-eye fa-2x">发现</vha-tab-item>
              <vha-tab-item icon="fa fa-user fa-2x">我的</vha-tab-item>
            </vha-tabbar>
            <div class="_ph-2x"></div>
            <vha-tabbar color="info" :followMeta="false">
              <vha-tab-item icon="fa fa-home fa-2x">主页</vha-tab-item>
              <vha-tab-item icon="fa fa-commenting fa-2x">消息</vha-tab-item>
              <vha-tab-item icon="fa fa-eye fa-2x">发现</vha-tab-item>
              <vha-tab-item icon="fa fa-user fa-2x">我的</vha-tab-item>
            </vha-tabbar>
            <div class="_ph-2x"></div>
            <vha-tabbar color="warning" :followMeta="false">
              <vha-tab-item icon="fa fa-home fa-2x">主页</vha-tab-item>
              <vha-tab-item icon="fa fa-commenting fa-2x">消息</vha-tab-item>
              <vha-tab-item icon="fa fa-eye fa-2x">发现</vha-tab-item>
              <vha-tab-item icon="fa fa-user fa-2x">我的</vha-tab-item>
            </vha-tabbar>
            <div class="_ph-2x"></div>
            <vha-tabbar color="error" :followMeta="false">
              <vha-tab-item icon="fa fa-home fa-2x">主页</vha-tab-item>
              <vha-tab-item icon="fa fa-commenting fa-2x">消息</vha-tab-item>
              <vha-tab-item icon="fa fa-eye fa-2x">发现</vha-tab-item>
              <vha-tab-item icon="fa fa-user fa-2x">我的</vha-tab-item>
            </vha-tabbar>
            
            <div class="_ph-2x"></div>
            <vha-tabbar color="dark" :followMeta="false">
              <vha-tab-item icon="fa fa-home fa-2x">主页</vha-tab-item>
              <vha-tab-item icon="fa fa-commenting fa-2x">消息</vha-tab-item>
              <vha-tab-item icon="fa fa-eye fa-2x">发现</vha-tab-item>
              <vha-tab-item icon="fa fa-user fa-2x">我的</vha-tab-item>
            </vha-tabbar>
            <div class="_ph-2x"></div>
            <vha-tabbar color="calm" :followMeta="false">
              <vha-tab-item icon="fa fa-home fa-2x">主页</vha-tab-item>
              <vha-tab-item icon="fa fa-commenting fa-2x">消息</vha-tab-item>
              <vha-tab-item icon="fa fa-eye fa-2x">发现</vha-tab-item>
              <vha-tab-item icon="fa fa-user fa-2x">我的</vha-tab-item>
            </vha-tabbar>
            <div class="_ph-2x"></div>
            <vha-tabbar color="stable" :followMeta="false">
              <vha-tab-item icon="fa fa-home fa-2x">主页</vha-tab-item>
              <vha-tab-item icon="fa fa-commenting fa-2x">消息</vha-tab-item>
              <vha-tab-item icon="fa fa-eye fa-2x">发现</vha-tab-item>
              <vha-tab-item icon="fa fa-user fa-2x">我的</vha-tab-item>
            </vha-tabbar>
            <div class="_ph-2x"></div>
            <vha-tabbar color="light" :followMeta="false">
              <vha-tab-item icon="fa fa-home fa-2x">主页</vha-tab-item>
              <vha-tab-item icon="fa fa-commenting fa-2x">消息</vha-tab-item>
              <vha-tab-item icon="fa fa-eye fa-2x">发现</vha-tab-item>
              <vha-tab-item icon="fa fa-user fa-2x">我的</vha-tab-item>
            </vha-tabbar>
          </div>
          
          <!-- <p class="_UI-title">自定义 ：</p>
          
          <div class="_UI-showBox">
            <vha-tabbar type="base" :followMeta="false">
              <vha-tab-item icon="fa fa-home fa-2x">主页</vha-tab-item>
              <vha-tab-item icon="fa fa-commenting fa-2x">消息</vha-tab-item>
              <vha-button class="ui-t-b-div _cl-fff _bc-error" type="none" icon="fa fa-plus fa-2x"></vha-button>
              <vha-tab-itemvha-tab-item icon="fa fa-eye fa-2x">发现</vha-tab-item>
              <vha-tab-item icon="fa fa-user fa-2x">我的</vha-tab-item>
            </vha-tabbar>
          </div> -->
          
          <p class="_UI-title"></p>
        </vha-scrollview>
      </vha-subview>
      <vha-subview>
        <vha-tabbar type="base" :followMeta="false">
          <vha-tab-item icon="fa fa-home fa-2x">主页</vha-tab-item>
          <vha-tab-item icon="fa fa-commenting fa-2x">消息</vha-tab-item>
          <vha-button class="ui-t-b-div _cl-fff _bc-error" type="none" icon="fa fa-plus fa-2x"></vha-button>
          <vha-tab-item icon="fa fa-eye fa-2x">发现</vha-tab-item>
          <vha-tab-item icon="fa fa-user fa-2x">我的</vha-tab-item>
        </vha-tabbar>
<!--         
        <vha-tabbar :followMeta="false">
          我是页内标签栏
          <br>
          我禁止了跟随mata判断隐藏
        </vha-tabbar> -->
      </vha-subview>
    </vha-view>
  </vha-page>
</template>
－－－－－－－－－－－－－－－－－－－－－－－－－－－－－－－－－－－－－－－－－－－－－
<script type="text/ecmascript-6">
export default {
  name: 'componentsPGtabBar',
  data() {
    //动态数据
    return {
    }
  },
  components: {
    //组件 - 引入或定义
  },
  methods: {
    //方法 - 进入页面创建
  },
  watch: {
    //观察 - 数据或方法变动
  },
  mounted() {
    //挂载实例后 - this.$el存在
  },
  beforeDestroy() {
    //销毁前 - 实例仍然完全可用
  }
}
</script>