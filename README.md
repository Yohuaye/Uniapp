# Uniapp
个人小程序项目
beta 1.0.0

问题：  
  1.楼层图片中  v-if属性添加在 view或者navigator 标签中效果无效
    原因未知.添加在img标签中可以正确过滤
  
  2.接口服务器返回的分类页图片URL有误
    获取到图片地址后，进行替换可正常使用
    
  3.商品列表的自定义小组件价格处理器无效
    原因未知，尚未解决
   
  4.默认空图片设置无效，大量数据的图片地址无效

  5.store引入vue报错
  'default' is not exported by node_modules\@dcloudio\uni-mp-vue\dist\vue.runtime.esm.js, imported by F:\UniApp\MyDemo\store\store.js
  原因不明，尚未解决


beta 1.1.0

  关于问题 1 2 3 5 原因均为vue版本不兼容，以解决
  问题4 接口服务器提供的地址已被删除，因而无法获取数据
