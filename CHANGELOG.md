# 2020-12-9 v0.2.6

- 修复用户行为堆栈数据过大的问题

# 2020-12-4 v0.2.5

- 优化script标签的属性性能，适配预渲染
- 缩小录屏插件的上报数据
- 优化自定义插件数据的限制
- 增加上报脚本版本号
- 解决img标签为空时的报错信息
- 优化行为堆栈白名单的判断，减少数据量
- 异常数据中不包含性能数据
- 增加过滤sockjs-node的常见调试报错

# 2020-11-18 0.2.4（v0.2.3有问题）

- 优化Edith对象的属性及其原型链展示
- 优化行为堆栈的bug
- 加快监控错误的时机

# 2020-09-21 v0.2.2

- 修复对Promise的polyfill的判断

# 2020-09-16 v0.2.1

- 增加silentHttp是否监听网络错误的参数

# 2020-09-16 v0.2.0

- 自定义插件数据，字段统一处理
- 增加上报cookie

# 2020-09-16 v0.1.11

- 修复http请求header和body的获取
- 增加webSokect监听错误和堆栈记录
- 增加错误过滤，以及控制Promise监听，资源加载监听、webSocket、是否上报http的body的参数
- 修复Promise不支持的解决方法
- 修复开发环境下不能上报自定义错误的bug

# 2020-08-22 v0.1.10

- 修复网络请求报错的判断
- 修复部分bug

# 2020-8-19 v0.1.6

- 修复插件安装使用问题

# 2020-8-19 v0.1.2

- 修复插件打包bug

# 2020-8-19 v0.1.1

- 修复自检bug

# 2020-8-19 v0.0.9

- 上报错误后，state需要清空，防止产生无用数据

# 2020-8-19 v0.0.8

- 修复npm包的问题

# 2020-8-19 v0.0.7

- 优化生命周期，增加自检
- 解决请求记录没有时间戳的问题

# 2020-8-18 v0.0.6

- 重构代码逻辑，拓展功能改为插件引入

# 2020-8-11 v0.0.5

- 更改请求地址
- 请求错误监听的逻辑

# 2020-7-30 v0.0.4

- 更改检测网速的请求方法
- 优化部分包大小
- 增加主动埋点上报功能
