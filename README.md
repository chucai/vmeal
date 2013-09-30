Vmeal
=====================
***一个在线订餐平台，店家可以在这里开店，用户可以购买商品.***
演示地址: www.weidaxue.me


###项目依赖###

1. ruby(1.9.x) + rails(3.2.x)
2. redis
3. mysql


###如何启动#####
*. clone代码 `git clone git@github.com:dianrui/vmeal.git`
*. 修改配置文件（database.yml）
*. 执行bundle命令 `bundle `
*. 启动redis `redis-server`
*. 执行 `rake db:create`
*. 执行 `rake db:migrate`
*. 执行 `rake db:seed`
*. 执行 `rails s`

###有哪些功能#####

1. 商家在线开店
2. 商家自主管理自己的店
3. 用户可以在线订餐
4. 订单实时推送
5. 订单状态短信提醒
6. 签到系统
7. 抽奖系统
8. 积分系统
9. 第三方登录和分享
......

###核心开发人员#####
1. [songjiayang](https://github.com/songjiayang)
2. [yinchangxin](https://github.com/YinChangXin)
3. [renkai](https://github.com/Ailenswpu)
4. [tuxiaozhong](https://github.com/tuoxiaozhong)
5. [zhaohang]()


###问题反馈###
https://github.com/dianrui/vmeal/issues

###License###
[GNU Affero GPL 3](http://www.gnu.org/licenses/agpl-3.0.html)







