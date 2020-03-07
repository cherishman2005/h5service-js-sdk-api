# h5service

## h5service-yy-appname版本说明

h5service-yy.min.js仅支持webh5，微信小程序。

## 动态

[2019-03-06] 【h5service-yy-appname js-sdk新版本】提供h5service-yy.min.js  1.0.4版本发布（VERSION = 1583493805）

（1）new NewH5(thirdUdbAppId: string="", miniAppId: string="", bReLoginAlways: boolean=false, udbAppId: string, udbAppSign: string)

【注】与以前版本兼容。new NewH5 新增参数udbAppId和udbAppSign。另外udbAppSign需要通过计算工具得到；

如果不填，默认appname='yymwebh5'；如果填写，请业务填写正确的udbAppId和udbAppSign。

【验收条件】：

	（1）service通道登录成功；
	（2）后端服务统计到预期的appname；


## npm包路径

https://www.npmjs.com/package/h5service-yy-appname