# 官方APP-活动-许愿树
- 修改日期：2017-10-20
- 进度：100%  
- 参与人员：zhangyuan 

## 修改记录
- 2017-10-19
* 测试用户有APP在APP打开，没有APP去应用市场下载，（setTimeout,先执行跳转去APP，几秒之后跳转应用市场，visiblechange事件可判断是否转换浏览器，有浏览器切换的时候不执行跳转应用市场）
- 2017-09-26
* 为了修复返回两次的问题，与app联调，app登录之后回到之前的页面，传来跳转地址，唤醒nt_reflash的方法  by zhangyuan
- 2017-09-25
* 修复ios登录返回页面图片不能加载的问题（其中调用ios清空历史记录的方法会导致部分资源加载失败，然后用了window.location.replace的方法修复当前bug,然而发现，这样做会导致一个新的问题，需要返回两次）  by zhangyuan
- 2017-09-22
* 修改活动文案  by zhangyuan
- 2017-08-04
* 增加活动结束显示未许愿页面相应逻辑  by zhangyuan
- 2017-07-28
* 修改bug  by zhangyuan
- 2017-07-21
* 完成全部页面逻辑，连接接口  by zhangyuan

- 2017-06-09
* 完成部分页面逻辑  by zhangyuan

- 2017-06-02
* 完成"愿望弹幕"逻辑  by zhangyuan

- 2017-05-21
* 完成抽奖、活动规则、浇水、小树成长、获奖结果静态页面 by zhangyuan

- 2017-05-21
* 完成填写地址、获奖名单、我的获奖静态页面 by zhangyuan

- 2017-05-21
* 完成首页、填写愿望静态页面 by zhangyuan

## 资料
- 原型（http://lfo62t.axshare.com/#g=1&p=愿望树)
- [接口文档](http://118.178.185.211:12304/cpappweb/document/cpappweb.xml)




