# 独家折扣小程序

#### 项目介绍
独家折扣 优惠券微信小程序，包含领券抽奖图片分享多种功能


#### 目录介绍
- [x] wechat   小程序源码

- [x] server    php后端源码

#### 温馨提示

因为微信方面原因，此类优惠券小程序很难上架审核通过，即使审核通过也很容易封号，代码仅供参考。

[同款APP已经上线，可去下载查看](http://down.kiwifruits.cn/)


#### 部分页面预览图
<img src="https://github.com/wkiwi/WeChatDJZK/blob/master/demo/1.jpg" width="365" height="619"/>
<img src="https://github.com/wkiwi/WeChatDJZK/blob/master/demo/2.jpg" width="365" height="619"/>
<img src="https://github.com/wkiwi/WeChatDJZK/blob/master/demo/3.jpg" width="365" height="619"/>
<img src="https://github.com/wkiwi/WeChatDJZK/blob/master/demo/4.jpg" width="365" height="619"/>
<img src="https://github.com/wkiwi/WeChatDJZK/blob/master/demo/5.jpg" width="365" height="619"/>
<img src="https://github.com/wkiwi/WeChatDJZK/blob/master/demo/6.jpg" width="365" height="619"/>
<img src="https://github.com/wkiwi/WeChatDJZK/blob/master/demo/7.jpg" width="365" height="619"/>
<img src="https://github.com/wkiwi/WeChatDJZK/blob/master/demo/8.jpg" width="365" height="619"/>
<img src="https://github.com/wkiwi/WeChatDJZK/blob/master/demo/9.png" width="365" height="619"/>
<img src="https://github.com/wkiwi/WeChatDJZK/blob/master/demo/10.jpg" width="365" height="619"/>
<img src="https://github.com/wkiwi/WeChatDJZK/blob/master/demo/11.jpg" width="365" height="619"/>
<img src="https://github.com/wkiwi/WeChatDJZK/blob/master/demo/12.jpg" width="365" height="619"/>
<img src="https://github.com/wkiwi/WeChatDJZK/blob/master/demo/13.jpg" width="365" height="619"/>

#### 简介


小程序首页由轮播图、分类、定向购、每日精选四大板块构成，轮播图可放置每天热销商品促进该商品销售，商品分类可让用户对商品进行种类筛选，定向购又分为淘抢购、聚划算、每日上新、9.9包邮，该几大模块可进入不同场景筛选出该场景商品，接下来为每日精选，显示当天销量前100的商品。

搜索页分为两大模块，内部搜与超级搜，内部搜搜索出来的商品，用户可以进行价格、销量、人气排行等排序，超级搜直接进入阿里妈妈商品库进行搜索商品信息全数量多，但用户无法对商品信息进行自定义排序显示，大家都在搜每天都会更新，智能显示用户搜索前15个关键词，搜索历史会保存该用户的最近搜索的10个关键词。

商品分类页面，用户可以自主筛选商品种类，且自定义排序显示商品信息。

个人中心页面包含三大功能区，个人资料、每日签到、我的工具。

商品信息显示对应商品的详细资料，包含商品轮播图、商品标题、在售价格、券后价格、券额、销量、推荐语句、店铺标题、店铺logo、店铺评分、商品评价、商品的详细图文、商品的产品规格....

用户点击立即领券，即可自动复制该商品的优惠券淘口令，打开手机淘宝即可完成领券。


用户在商品详情页可点击分享转发按钮，会将对应的该商品信息分享出去，别的用户点击可直接进入对应的商品详情页。

用户在商品详情页点击生成分享图按钮，会生成对应商品的图片保存在手机，用户可对该图片进行转发，别的用户可用微信扫描该图片的二维码可直接进入对应商品详情页。

为了增加引流，反馈老用户，吸纳新用户，特开发此模块，用户在有抽奖活动的情况下，从个人中心 我的工具 点击抽奖进入时可点击参与抽奖按钮，参与抽奖。


发起抽奖按钮在该用户添加为管理员的情况下，进入个人中心可显示发起抽奖按钮，管理员进入抽奖页面，需要填写抽奖名称、抽奖数量1-5个、开奖时间、奖品简介等信息，到时间后管理员需手动点击开奖按钮，程序会自动根据 参与人数以及设定人数，随机挑选出中奖用户，且同事间，小程序后台会对参与此次开奖结果，对参与抽奖用户进行消息推送。