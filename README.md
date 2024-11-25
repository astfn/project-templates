技术栈

- vue3.5 + ts + vite + vant

模板功能点

1. 版本更新提示

2. 登录成功后自动进入用户上一次进入的页面（token过期）

3. 微信授权基础逻辑

4. 全局基础布局的维护

   - 布局信息在整个 app 中都可访问（维护到了 store 中），让页面布局更加灵活

     > 更加灵活？
     >
     > - 因为现代 h5 开发很多都是需要嵌入到 小程序 或者 app 中，有时需要根据不同的环境对布局或样式进行调整，组件中可以根据当前的布局信息进行准确的调整。

5. 请求工具函数的封装

   - 支持缓存模式和 cancel 模式

6. 基础 hooks 的封装