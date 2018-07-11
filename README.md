# Wepy微信小程序商城
基于腾讯团队[Wepy](https://tencent.github.io/wepy)框架开发的微信小程序商城，包含下单支付、物流、便捷支付、购物车、商品评价等功能，长期维护版本，欢迎大家踊跃提交贡献代码。

<b> 如果本文能对你提供到一点小小的帮助，请赏给作者一个 ***Star*** 吧！</b>

## 后期版本

增加拼团秒杀、卡劵、配送物流功能。针对此程序有其他改进的想法或建议欢迎大家同我一起交流沟通~

## 参与开发

更多项目请关注 [https://github.com/FansOne](https://github.com/FansOne)。

开发问题欢迎一起交流,扫码添加VX：<img src="https://wx-shopping-1257093177.cos.ap-beijing.myqcloud.com/WX.jpeg" width="222px" height="222px" style='inline'>

## 项目截图

<img src="https://wx-shopping-1257093177.cos.ap-beijing.myqcloud.com/1531289849173.jpg" width="375px" height="667px">
<img src="https://wx-shopping-1257093177.cos.ap-beijing.myqcloud.com/WechatIMG1.jpeg"   width="375px" height="667px">
<img src="https://wx-shopping-1257093177.cos.ap-beijing.myqcloud.com/1531281008803.jpg" width="375px" height="667px">
<img src="https://wx-shopping-1257093177.cos.ap-beijing.myqcloud.com/1531281050452.jpg" width="375px" height="667px">
<img src="https://wx-shopping-1257093177.cos.ap-beijing.myqcloud.com/1531281085303.jpg" width="375px" height="667px">
<img src="https://wx-shopping-1257093177.cos.ap-beijing.myqcloud.com/1531281118772.jpg" width="375px" height="667px">

## 扫码体验

> 程序入口
>
<img src="https://wx-shopping-1257093177.cos.ap-beijing.myqcloud.com/join.jpeg" width="245px" height="260px">

> 便捷支付
> 
<img src="https://wx-shopping-1257093177.cos.ap-beijing.myqcloud.com/pay.jpeg" width="245px" height="260px">

## 最新功能

- 新增到店支付买单功能，扫码上面第一个二维码，可体验便捷支付；
- 分享商品给好友，好友下单后可获得积分、现金返现；
- 可修改订单默认30分钟未支付被关闭的时间；

## 使用说明

> [申请商城后台账号](https://www.it120.cc/info/wxapp/115)
>
> 选择使用商城模块
> > 在 API 列表中选择使用以下API模块：
>
> > >系统参数设置： 用于配置商城名称；
>
> > > 小程序用户注册接口：实现用户注册；
>
> > > 小程序登录接口：实现用户自动登录；
>
> > > App Banner管理接口: 设置商城首页轮播图片
>
> > > 在线支付接口：完成小程序在线支付；
>
> > > 商品类别接口；
>
> > > 商城商品管理接口；
>
> > > 商城订单管理接口；
>
> > > 用户收货地址接口；
>
> > > 优惠券接口；
>
> > > 平台公告模块
>
> > > 积分模块【签到送积分】
>
> 修改源码中  app.js 文件
> > > globalData:{
>  userInfo:null,
>  subDomain:"mall"
>}
> >
> > > subDomain 中的 mall 为上面您注册开通的域名
>
> [设置小程序合法服务器域名](https://www.it120.cc/info/wxapp/116)
>
> 重启您的小程序开发工具，完成

## 常见问题

- [如何修改小程序商城的标题？](https://www.it120.cc/info/faq/778)
- [“无法登录”的错误？](https://www.it120.cc/info/faq/391)
- [小程序提示“无法登录”的错误？](https://www.it120.cc/info/faq/392)
- [如何发布自己的商品？](https://www.it120.cc/info/faq/436)
- [如何给Banner增加链接，点击打开某个商品？](https://www.it120.cc/info/faq/437)
- [获取我的accesstoken，以便我在其他系统使用](https://www.it120.cc/info/faq/763)
- 工厂后台设置 appid、secret、微信支付商户号和秘钥时候的 token 怎么填？
>  不要填！
>
>  不要填！
>
>  不要填！
>
> 重要的事情说三遍，这个小程序用不到，是给服务号使用的，所以大家空着不要填
- 微信支付时候，提示 50000 错误，不能获取到预支付id
>  这个错误是无法获取到微信支付的预支付信息
> - 可能是你没有在后台配置您的微信支付商户号和秘钥，或者配置错误
>
> - 可能是你配置的微信支付不是当前小程序申请的（微信支付目前无法跨小程序调用）
>
> - 确保微信开发工具上面登录的 APPID 和你在后台配置的 APPID 是同一个
- 能否帮我免费添加功能？
> 可以！
>
> <img src="https://cdn.it120.cc/apifactory/2017/07/29/18ae9b8aaedcd747fc5f1c3fa8bc0fe4.png" width="300px">
>
> - 点击页面顶部的 Star ，关注后，项目有最新动态 github 会提醒您，不错过重要更新；
> - 点击页面顶部的 Fork， 将您需要增加的功能完成 小程序 端界面的调整，然后在 github  上请求将您的代码合并到 EastWorld；
> - 您的代码合并请求审核通过后，我们将会为您完善配套的后台功能；
> - 开源项目离不开您的支持和代码共享，我们一起把 EastWorld 项目长期维护下去；
- [如何使用在线客服功能？](https://www.it120.cc/info/faq/867)
- 下单的时候没有地方填写收货地址？
> 1、添加一个“物流模板”，只有需要快递的商品才会提示用户填写收货地址
>
> 2、发布商品的时候，选择刚才添加的“物流模板”
>
> 3、重新下单，将会需要用户输入收货地址
- 后台设置appid和secret的时候提示不正确？
> 1、请确认您填写的appid和secret是否正确
>
> 2、输入的时候确保没有空格（复制的时候可能会多复制了空格）
>
> 3、在微信后台设置服务器IP地址白名单（106.14.43.122）
- 如何使用退款功能？
> 1、后台支持针对订单指定退款多少金额；
>
> 2、可选择退款至用户可用余额或者按照用户支付原路退还第三方或者银行卡；
>
> 3、如果选用原路退还，需要在商户号和秘钥设置的地方上传您的微信支付证书文件（PK12格式文件）
- 如何设置满多少包邮？
> 1、后台系统设置 --> 系统参数，增加系统参数；
>
> 2、参数名 free_shipping_for_purchases （注意不要有空格）
>
> 3、参数值填写您希望的买满金额即可
- [“规格与尺寸”怎么玩](https://www.it120.cc/info/faq/1208)
- [如何设置用户提现手续费](https://www.it120.cc/info/faq/1589)
- [商品如何显示视频？](https://www.it120.cc/info/faq/1802)
- [货到付款、积分赠送规则设置](https://www.it120.cc/notice/22)
- [小程序如何使用“模板消息”给用户推送消息](https://www.it120.cc/info/faq/2823)
- 如何修改或者关闭订单超过30分钟未付款自动关闭？
> 1、创建订单接口增加 expireMinutes 参数；
>
> 2、代表多少分钟未支付自动关闭本订单，传0不自动关闭订单；


## 如何升级到最新版

- 小程序程序的修改和您后台的数据是独立的，所以不用担心您会丢失数据
- 先把你开发工具下的现有版本程序备份
- 下载最新版的程序，直接覆盖您本地的程序
- 用开发工具修改域名 mall 为你自己的域名
- 开发工具里面上传代码提交微信审核
- 审核通过后，小程序后台去发布新版本即可
- 用户无需重新扫码，关闭小程序重新打开就是新版本了
