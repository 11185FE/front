# 新春拜年
截止日期：2017-02-04  
修改日期：2017-01-19  
进度：100%  
参与人员：chenzhaolong huangshuyi


## 修改记录
- 11
修改文案

- 10
关闭ajax 状态码0报错
调整jssdk调用时刻

- 9
1.没有发送过祝福，点击我的祝福，没有任何提示，建议添加提示
2.领奖填写地址以后，点击确定，提示修改成功？
3.去拜年那个页面，人物有遮挡
4.点击我的祝福 加载比较慢 然后切换成4G后出现
5.填写地址的时候，键入文字，输入框会上移，且图片和输入框会被遮挡，地址框不能移动（安卓）
6.声音按钮会被页面图片遮挡部门
7.重新打开微信，再打开链接，会有一个提示，应该是user:0什么的，闪得太快

只能改135
2本来就有提示
6声音按钮白色一直在最上
47网络问题无法处理
- 8
根据接口变动修改nicknameutf8 为 nickname
改为点一个祝福，就调用addGoods接口吧，而不是点“发送”才调用
导致hash模式要点2次返回才能离开wish页

- 7
修改接口报错处理方式

- 6
修改文案

- 5
我的中奖列表  昵称=》对方昵称
特定弹框不能阴影关闭
分享抽奖链接 朋友圈分享除外

- 4
去除邮政编码判断

- 3
祝福详情页设备尺寸兼容
声音控制和图标

- 2
w的祝福页面，点击每个祝福，进入该祝福的详情页面。
分享文案

- 1
说明文案补充  
修复IOS音乐  
修改狮子结束行为



## 开发记录
开发完成  
功能2 chenzhaolong  
功能  huangshuyi  
静态页面完成 chenzhaolong  
框架完成 chenzhaolong  

## 文档
- 接口
http://www.doyoteam.com:8082/showdoc-master/index.php?s=/4  


- 需求
http://twghoy.axshare.com  

- 需求补充

-------
未中奖提示语：  
万事如意，阖家幸福  
福星高照，万事亨通  
新春快乐， 福寿安康   
岁岁平安， 年年有余  
福星高照 ，恭贺新春  
吉祥如意，五福临门  
荣华富贵， 金玉满堂， 鹏程万里  
红红火火 ，事业有成 ，心想事成， 一帆风顺  
这些是随机出现的  


------
都是已发送。没有未发送这个状态  
是不是要分享了 才算已发送  

------
自己不可以点自己的分享抽奖  

------
如果分享到朋友圈，只能是分享这个活动。不能是分享单个祝福。  
发送给某个好友，才可以发送祝福。  

------
新的一年，有些话要悄悄告诉你。  
发送祝福：XXX向你发来了新年的祝福，还有神秘礼物哦~   

------

对，每接收到一个祝福只能抽一次奖  

-------


祝福列表都显示发送的  

--------