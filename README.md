
### 项目介绍
- 项目说明： 支持个人网站、安卓App、微信公众号、Pc软件收款的接入，所有的资金都会实时到账您的支付宝/微信余额中，支付宝无需上传收款二维码，支持H5唤醒支付，支持回调通知、支持补单、后台功能简单。

- 特点：支付回调通知，0手续费实时到账（不经过任何第三方，直接到账微信/支付宝余额），全部服务端源代码，支持php/java/python等语言直接接入(请使用Api版本傻瓜式接入)，监听方式非xp框架HOOK的方式，独立App监听安全无风险，无需root权限。

- 实现原理： 当收到支付宝、微信、实时收款信息，客户端会实时通知服务器收款金额和方式，服务器收到有效期订单金额后处理订单状态，使用随机减免的方式区分订单（5分钟订单有效期内有相同金额的订单会随机减免0.01 - 0.10的方式用来区分订单。

### 在线demo
- 本项目演示地址： [点此测试](http://wzpay.jmkeji.net)

### 开始部署
- 本项目源码下载： [点此下载](http://wzpay.jmkeji.net)

### 系统功能

- 商户后台功能: 
  
   1.商户基本信息 、收款账号设置、申请提现功能、登入日志、支付宝，QQ快捷登入。

   2.商户公告:【商户公告可后台增删改查】。

   3.商户排行榜:【根据网站商户的交易金额进行排行，前10名】。

   4.订单交易记录:【每条已经完成支付的订单都可以进行重新回调通知】。

   5.结算记录: 【显示每天已经结算至收款账号的相关记录】。

   6.支付测试:【商户可以直接在后台进行网站支付接口调用测试】。

   7.商户转账 、商户转账记录:【实现商户与商户之间的转账，设置支付密码后才可转账】。 

   8.邀请返利、邀请返佣金记录:【只要通过商户邀请id注册的商户，都可以获得后台设置的返佣金额并且记录】

   9.集成包插件: 【支持后台增删改查】

  10.会员功能: 【分3个会员组：普通会员[单笔3%费率]、黄金会员[单笔2%费率]、钻石会员[单笔2%费率或1%费率 另有提现秒到账的特权】。



- 管理后台功能：

  1.网站管理、基本配置、商户配置、监控配置。

   2.平台管理、公告配置、广告配置、插件管理。

   3.订单管理、【支持对已经完成支付的订单进行回调通知】。

   4.转账管理、【支持对转错账的商户，操作退款】。

   5.邀请记录、【可查询所有邀请信息，以及返佣情况】。

   6.结算管理、结算记录、【结算操作、可以手动转账，也支持企业支付宝与微信企业转账结算】。

   7.商户管理、合作者商户管理【商户增删改查】。
 
   8.接口配置、【包含: 官方支付宝wap+pc、支付宝当面付、微信pc扫码、jsapi公众号支付、微信h5支付、QQ官方支付、集成易支付第四方支付、码支付个人免签支付、】。

   9.多官方接口、【支付宝官方、微信官方、QQ官方、带多接口轮训】。


- 本系统类似于ABC、好好云 、abl云、 易支付、 一样的程序 ，如您网站本身是对接的 以上的某家支付 ，那您根本不需要在开发接口了，您直接搭建好此程序， 配置好接口，即可正常调用。


### 程序更新日志：

20191105更新：

1.优化商户登陆注册找回相关代码与修复已知bug。

2.新增图形验证码功能，美化商户注册登陆UI界面。

20190715更新：

1.增加支付宝微信QQ商品说明自定义后台可以单个设置【效果往下看首 张图】此功能可以起到商户监督功能，如商户的网站存在付款不给货，那付款用户可以联系QQ进行投诉。



20190710更新：

1、增加网站页面恶意刷新拦截。

2、新增：微信、QQ、支付宝、普通会员、黄金会员、钻石会员、全部单独费率设置功能。



20190708更新：

1.商户后台更新新UI布局。

2.增加商户后台支付在线测试功能

3.增加商户与商户之间互相转账功能【此功能有写安全监测风控】

4.邀请推广功能【商户邀请用户注册后，得相应的金额奖励】此功能可以后台关闭；

5.增加商户排行榜，【只显示前10名商户排行】、

6.增加集成包插件【后台支持上传，商户后台下载】、

7.增加广告功能【后台支持增删改查。此功能信息显示在商户首页底部】。

8.后台增加转账管理【支持对转错账的商户，进行退款操作】。

20190701更新：

1.增加商户登入安全验证码设置新规则【需要邮箱验证修改】

2.增加后台主题ul颜色切换功能【后台可以自动切换颜色背景】

3.增加商户免费注册开关【开启则需要支付对应金额注册商户，关闭则直接注册无需付款注册】

4.对接全新的授权系统，支持在线购买授权了。

20190630更新：

1.重写商家登入与注册规则，从原来的商户号秘钥登入改为账号密码登入

2.改版新登入注册找回ul页面

20190626更新：

1.增加支付监控

2.增加第四方监控自动补单功能

3.后台增加支付测试开关功能

4.增加后台登入日志记录

20190624更新：

1.增加新模板UI ，后台可以随意切换，【共三官方模板选择】

2.优化目录结构，优化部分代码，增加php防注入和XSS攻击通用过滤,

3.增加友情链接、用户协议。均可后台修改。

20190618更新：

1.更新后台UI，商户后台UI

2.修复商户注册问题

3.完善商户功能

4.完善后台基本功能

5.增加支付宝QQ授权登入【支持后台设置】

5.增加seo设置与网站维护开关功能



20190528更新：

1.增加用户安全码，修改商户信息需要输入安全码二次验证，有效防止商户信息被恶意篡改

2.增加VIP用户组到期时间限制

3.增加VIP用户组包月和包年套餐

4.增加黄金VIP和钻石VIP用户组功能（享受低费率和手动申请结算即时到账特权）
5.完善商户手动申请结算功能（钻石vip可D0到账 普通商户T+1到账）
6.增加官方接口多账户轮询功能（每个账户满多少额度以后自动切换使用下一个账户）
7.支付宝当面付接口可以在网站后台直接设置了


