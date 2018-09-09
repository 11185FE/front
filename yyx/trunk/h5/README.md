# 邮印象 - h5版
修改日期：2018-09-07
进度：100%
参与人员：guxionghong zhangyuan yerenming

## 修改记录
- 2018-09-07
  * 新增修正图片旋转信息方法 guxionghong
  * 兼容 ios、安卓下，缩略图 exif 信息差异问题 guxionghong
  * 修复 ios 下图片旋转后裁剪信息错误 bug guxionghong

- 2018-08-31
  * 新增支持微信选图功能
  * 重构 canvas 渲染逻辑
  * 重构作品图片保存逻辑
  * 修复oss图片上传bug
  
- 2018-07-13
  * 更新npm包，修复安卓机图片缩放无限放大bug

- 2018-04-20
  * 研究有福微信版制作流程，结论：有福的制作流程与邮印象流程差异为，有福制作不需要在客户端对图片进行裁剪以及截图操作，读取图片方式是一致的，在部分机器上依旧存在读取图片后黑图情况
  * 研究微信版优化方案（暂无结果）
  
- 2018-04-10
  * 测试环境加入 jenkins 自动构建

- 2018-03-28
  * 新增多人定制帮助引导功能 guxionghong

- 2018-03-22
  * 修复使用帮助、免责声明头部声明 guxionghong
  * 修改商品订单金额取值方式 guxionghong

- 2018-03-19
  * 部署生产环境 guxionghong
  * 邮印象测试跟生产环境切换新域名 guxionghong
  * 修改图片加载方式 guxionghong

- 2018-03-12
 * 新增oss图片服务 guxionghong
 
- 2018-03-07
 * 修复手机号绑定，错误验证码仍提示绑定成功bug  guxionghong

- 2018-02-26
 * 新增智能客服功能 guxionghong
 * 修复智能客服相关bug guxionghong

- 2018-01-31
  * 修复环邮中国对接环节，错误处理导致页面404bug guxionghong
  * 新增禁止环邮中国流程进入后的作品删除操作 guxionghong
  * 新增环邮中国作品重新编辑后的再推送操作 guxionghong

- 2018-01-25
  * 新增福利卡领取状态查询页面 guxionghong

- 2018-01-24
  * 去除多个页面标题栏 guxionghong
  
- 2018-01-19
  * 修复审核不通过重新编辑流程 guxionghong
  
- 2018-01-17
  * 福利卡下单新增线下支付 guxionghong
  * 新增删除订单功能 guxionghong

- 2018-01-15
  * 春节活动上线 guxionghong
  * 修复确认支付状态bug  guxionghong

- 2018-01-11
  * 新增春节活动抽奖页面 guxionghong
  
- 2018-01-10
  * 完成春节活动主题页面逻辑 guxionghong

- 2018-01-08
  * 完成春节优惠券领取页面 guxionghong
  
- 2018-01-05
  * 调整新版邮印象与环邮中国相关交互 guxionghong
  * 增加新版通用优惠券领取页 guxionghong

- 2018-01-04
  * 完成春节主题活动页静态页面 guxionghong

- 2017-12-27
  * 去除订单列表、订单详情头栏 guxionghong

- 2017-12-26
  * 修改营销员统计业绩起始时间 guxionghong
  * 修改审核失败重新编辑流程 guxionghong
  * 新增重新编辑JSBridge接口 guxionghong
  
- 2017-12-25
  * 订单列表、订单详情新增审核不通过状态 guxionghong
  * 订单详情新增重新提交审核功能 guxionghong

- 2017-12-05
  * 切换新版公众号登录方式 guxionghong

- 2017-12-01
  * 重构路由懒加载模块 guxionghong
  * 完成翻书效果组件 50% guxionghong

- 2017-11-17
  * 研究书本翻页效果 guxinghong
  * 添加用户地区来源识别逻辑 guxionghong

- 2017-11-13
  * 新增主动更新用户信息bridge方法 guxionghong
  * 新增微店名二次修改功能 guxionghong
  * 二维码组件新增logo跟导出图片功能 guxionghong

- 2017-11-10
  * 下单页面新增手机号判断逻辑 guxionghong
  * 新增二维码组件 guxionghong
  * 新增 navigateTo bridge 方法 guxionghong
  * 修复微店相关bug guxionghong

- 2017-11-09
  * 新增微店详情、微店管理页面 guxionghong

- 2017-11-08
  * 新增微店开通页面 guxionghong

- 2017-11-07
  * 新增用户手机绑定功能 guxionghong

- 2017-11-06
  * 研究微信传图sdk，无果，安卓机器都会显示模糊图 guxionghong

- 2017-11-03
  * 安卓微信版尝试采用微信sdk选图方式，优化内存使用 guxionghong

- 2017-11-01
  * 修改最低像素提醒逻辑 guxionghong
  * 物流信息新增 xss 文本过滤 guxionghong
  * 修改上传图片压缩限制值 guxionghong

- 2017-10-27
  * 修复微信初次分享出错bug guxionghong
  * 新增图片像素最低阈值判断提醒 guxionghong

- 2017-10-25
  * 新增错误日志统计功能 guxionghong
  * 新增订单退款、物流查询、订单确认等功能 guxionghong

- 2017-10-24
  * 新增使用帮助、免责声明页面 guxionghong
  * 新增长图作品在窄屏手机适配性  guxionghong

- 2017-10-23
  * 修复多作品预览图片切换 bug guxionghong

- 2017-10-20
  * 新增下载引导页 guxionghong
  * 新增微信登录code重定向页面 guxionghong

- 2017-10-19
  * 新增同学录分享页面 guxionghong

- 2017-10-18
  * 排查解决生产环境图片服跨域bug guxionghong
  * 多机器兼容性排查 guxionghong

- 2017-10-17
  * 修复大量bug，完成生产环境第一版上线 guxionghong
  * 修复订单确认页优惠券选取bug  guxionghong

- 2017-10-16
  * 修复订单确认页购买数量切换bug guxionghong
  * 修复微信无法登陆问题 guxionghong
  * 修改订单列表按钮逻辑 guxionghong
  * 修复分享遮罩点击穿透 bug guxionghong
  * 添加删除订单功能 guxionghong

- 2017-10-13
  * 重构订单详情页面 guxionghong
  * 重构订单确认页面 guxionghong

- 2017-10-12
  * 重构订单列表页面 guxionghong

- 2017-10-11
  * 新增免责声明页面及修改帮助页面文案 guxionghong

- 2017-10-09
  * 创建 邮印象 独立版本 guxionghong

- 2017-09-29
  * 接入 安卓 hybrid 版本 guxionghong

- 2017-09-27
  * 修复版本迁移引起的主题馆商品相关bug guxionghong
  * 接入 ios hybrid 版本 guxionghong

- 2017-09-26
  * 完善 native 交互代码 guxionghong

- 2017-09-25
  * 修改明信片不可选数量（固定1）逻辑 guxionghong
  * 新增福利卡下单最少10张逻辑 guxionghong
  * 修改我的页面排版样式 guxionghong

- 2017-09-22
  * 确认订单页面新增福利卡使用功能 guxionghong
  * 新增优惠券兑换功能 guxionghong

- 2017-09-21
  * 新增我的福利卡页面 guxionghong

- 2017-09-20
  * 新增重新编辑我的作品 guxionghong

- 2017-09-19
  * 新增 作品详情 删除、分享、复制功能按钮 guxionghong

- 2017-09-15
  * 重构Native基础交互库 guxionghong

- 2017-09-13
  * 重构基础网络库 guxionghong

- 2017-09-12
  * 修复安卓部分手机图片展示错误bug guxionghong

- 2017-09-11
  * 修改购物车样式 guxionghong
  * 修改我的作品提示逻辑 guxionghong
  * 新增同学录限制下单逻辑 guxionghong

- 2017-09-08
  * 新增用户信息修改页 guxionghong
  * 修复购物车bug、修改福利卡领取显示逻辑 guxionghong

- 2017-09-07
  * 修改分享页登录逻辑 guxionghong
  * 路由跳转新增 `replace` 功能，更新多处路由逻辑 guxionghong
  * 修复定制显示错误bug  guxionghong

- 2017-09-06
  * 完成定制购物车相关页面功能 guxionghong

- 2017-09-05
  * 修复自动绑定分享营销员信息逻辑 guxionghog

- 2017-09-04
  * 作品分享时不需要检测登录 guxionghong

- 2017-09-01
  * 调试作品购物车相关接口 guxionghong

- 2017-08-31
  * 修改我的作品页面逻辑 guxionghong

- 2017-08-30
  * 修复营销员id分享逻辑bug  guxionghong

- 2017-08-28
  * 修改多页制作显示逻辑 guxionghong
  * 修改我的作品排列样式 guxionghong
  * 作品订单购买数量限制上调至999 guxionghong

- 2017-08-25
  * 修复台历日期重影问题 guxionghong
  * 新增福利卡领取页面 guxionghong

- 2017-08-24
  * 所有页面分享新增营销员信息 guxionghong
  * 新增通过营销员分享页面，自动绑定及自动进行订单归属功能 guxionghong

- 2017-08-23
  * 福利卡产品详情页新增自定义金额功能 guxionghong

- 2017-08-22
  * 产品详情页新增产品切换功能 guxionghong
  * 修改台历默认年份 guxionghong

- 2017-08-16
  * 修改打包构建程序代码 guxionghong
  * 修复ios全局input出错问题 guxionghong
  * 修复台历作品保存顺序bug  guxionghong

- 2017-08-09
  * 新增台历制作field1字段 guxionghong
  * 新增多页作品继续制作功能 guxionghong

- 2017-08-07
  * 修改裁剪规则，实现300dpi裁图效果 guxionghong
  * 添加邮乐T恤活动错误拦截逻辑 guxionghong

- 2017-08-03
  * 对接邮乐app，修复大量安卓端兼容问题 guxionghong

- 2017-08-01
  * 研究新版编辑方式安卓崩溃问题 guxionghong

- 2017-07-28
  * 对接环邮中国 guxionghong

- 2017-07-26
  * 尝试各种方式修复安卓多页制作bug guxionghong

- 2017-07-25
  * 完成新版多页定制流程 guxionghong

- 2017-07-24
  * 修复明信片制作流程bug guxionghong

- 2017-07-21
  * 对接邮乐T恤活动页 guxionghong

- 2017-07-18
  * 完成新版作品列表 guxionghong
  * 完成新版作品预览页 guxionghong

- 2017-07-14
  * 开发微信版新的制作页 guxionghong

- 2017-07-13
  * 开发新版我的作品页面 guxionghong

- 2017-07-12
  * 修改多个页面，统一四端体验 guxionghong

- 2017-07-11
  * 新增lomo卡定制流程 guxionghong

- 2017-07-05
  * 新增福利卡制作流程 guxionghong

- 2017-06-29
  * 上线生产环境，修复bug guxionghong

- 2017-06-27
  * 新增定制首页 guxionghong
  * 新增模板详情页 guxionghong
  * 修改板式列表展示逻辑 guxionghong

- 2017-06-24
  * 修复反馈bug guxionghong

- 2017-06-21
  * 完成新版我的作品页面功能 guxionghong

- 2017-06-20
  * 新增两款马克杯定制流程 guxionghong

- 2017-06-17
  * 新增台历定制流程 guxionghong
  * oss服务经费有问题，项目改为兼容双版本图片服务 guxionghong

- 2017-06-16
  * 新增照片冲印定制流程 guxionghong

- 2017-06-15
  * 新增摆件、摆台定制流程 guxionghong

- 2017-06-14
  * 新增照片书、杂志定制流程 guxionghong
  * 修复safari使用oss跨域bug guxionghong

- 2017-06-12
  * 新增定制产品分类页 guxionghong

- 2017-06-10
  * 接通oss图片上传接口 guxionghong
  * 更新多个接口数据改造 guxionghong

- 2017-06-08
  * 新增T恤抽奖抽奖页 guxionghong

- 2017-06-06
  * 重构明信片制作流程 guxionghong
  * 增加定制流程分享逻辑 guxionghong
  * 新增我的作品页面 guxionghong

- 2017-06-05
  * 作品下单页新增数量选择 guxionghong

- 2017-06-03
  * 新增T恤制作流程 guxionghong
  * 订单相关页面修改兼容新产品 guxionghong
  * 新增作品预览页 guxionghong

- 2017-05-26
  * 对接多个新版本接口，接通照片书新流程 guxionghong

- 2017-05-24
  * 整理代码，封装工具类库 guxionghong

- 2017-05-23
  * 完善定制引擎，抛弃svg dom渲染文本方式，改用纯canvas渲染 guxionghong

- 2017-05-19
  * 抽象定制引擎组件，实现明信片背面信息绘制 guxionghong

- 2017-05-18
  * 完成照片书定制引擎流程 guxionghong

- 2017-05-13
  * 配合服务端做全接口改动 guxionghong

- 2017-05-11
  * 添加母亲节下单逻辑 guxionghong
  * 修改环邮中国下单逻辑 guxionghong

- 2017-04-24
  * 修改订单列表页面，新增多作品下单展示情况 guxionghong
  * 订单确认页新增多作品下单逻辑 guxionghong

- 2017-04-13
  * 修改明信片下单逻辑，包括封面图片上传、去除地址填写、添加环邮中国交互等 guxionghong
  * 修复我的优惠券数据错误bug guxionghong
  * 修复安卓机器无法正确读写图片类型bug guxionghong
  * 部署上线

- 2017-04-07
  * 改用按需加载加载页面 guxionghong

- 2017-04-06
  * 部署上线
  * 增加404页面 guxionghong

- 2017-04-05
  * 去除微信版手机绑定功能，调试对应接口 guxionghong
  * 我的页面新增地址管理功能 guxionghong
  * 图片裁剪工具添加旋转功能 guxionghong

- 2017-04-01
  * 完成照片冲印定制 guxionghong

- 2017-03-30
  * 完成摆件定制 guxionghong

- 2017-03-29
  * 完成海报定制 guxionghong

- 2017-03-23
  * 添加首页导航栏、摆件、海报、照片冲印产品介绍页 guxionghong

- 2017-03-21
  * 明信片定制功能上线，修复图片跨域不能处理等问题 guxionghong

- 2017-03-20
  * 解决安卓机裁剪卡死问题，发现ios裁剪失败原因 by guxionghong
  * 修复签名错误、订单失效等bug

- 2017-03-17
  * 修改网络交互层逻辑，兼容blob文件上传、主动编码等 by guxionghong
  * 新增多明信片预览，照片书、同学录、台历预板式预览页 by guxionghong

- 2017-03-16
  * 新增Touch通用组件 by guxionghong
  * 新增引导页通用组件 by guxionghong

- 2017-3-15
  * 完成明信片定制全流程 by guxionghong

- 2017-3-14
  * 新增编辑状态监测hoc组件 by guxionghong

- 2017-3-13
  * 微信第一版上线生产环境，修复bug by guxionghong
  * 修改营销员绑定页面分享方式 by guxionghong

- 2017-03-10
  * 修复n多个bug
  * 修复购物车下单页，出现购物车已被清空报错bug  guxionghong
  * 修改地址编辑页面逻辑 guxionghong

- 2017-03-09
  * 完成定制图片编辑页面开发 guxionghong
  * 修复主题馆列表图片显示错误bug guxionghong

- 2017-03-08
  * 修改微信支付方式，使用 weixinbridge 接入支付（jssdk的方式在安卓端出错） by guxionghong
  * 修改订单确认页优惠券领取逻辑 by guxionghong
  * 修复搜索非法字符出现的bug by guxionghong

- 2017-03-07
  * 接通微信支付，确认订单页、订单详情页接入支付功能 by guxionghong
  * 主题馆首页banner新增多图、链接及定时轮播功能 by guxionghong
  * 新增使用帮助页面 by guxionghong

- 2017-03-06
  * 修复主题馆列表不可滚动bug by guxionghong
  * 我的页面接入用户基础信息、营销员系统、订单、购物车、收藏、优惠券、地址等功能 by guxionghong
  * 接入微信分享，Img组件添加是否调用微信图片预览参数 by guxionghong

- 2017-02-27
  * 主题馆列表添加全局搜索功能及修复渲染出错bug by guxionghong

- 2017-02-24
  * 添加微信注册于绑定手机号页面 by guxionghong
  * 接入微信登录，修改native登录逻辑 by guxionghong
  * 修改签名方式，采用双次sha-256加密 by guxionghong

- 2017-02-23
  * 商品详情页接入地址选择功能 by guxionghong
  * 下单页添加无收货地址情况 by guxionghong
  * 接入生成订单接口 by guxionghong

- 2017-02-22
  * 添加商品详情页，数量不足时不可下单、添加购物车功能 by guxionghong

- 2017-02-21
  * 修改路由切换动画方式，实现监听返回页面操作 by guxionghong

- 2017-02-20
  * 订单结算页面开发 by guxionghong
  * 添加首页加载动画，优化首屏加载体验 by guxionghong

- 2017-02-16
  * 优惠券选择页面开发 by guxionghong

- 2017-02-14
  * 多联级选择组件开发 by guxionghong

- 2017-02-13
  * 收货地址列表页面开发 by guxionghong
  * 地址编辑页面开发 by guxionghong

- 2017-02-08
  * 进行订单支付页面开发 by guxionghong

- 2017-02-06
  * 整合营销员、全局搜索页等代码 by guxionghong
  * 修改页面跳转动画 by guxionghong

- 2016-12
  * 定制说明首页、明信片模板选择页、模板预览页、图片编辑功能开发 by guxionghong
  * 主题馆列表页、分类页，我的页面，优惠券页面开发 by yerenming

## 资料
- [readmine 地址](http://118.178.128.63:8030/projects/h5)

- [主题邮局 接口文档](http://118.178.128.63:8030/projects/api/wiki)

- [邮印象 接口文档](http://118.178.128.63:8030/projects/mypost-assamblly/wiki/邮印象接口文档)

- [测试环境](wx.yyx.doyoteam.com/weixin/#/custom)