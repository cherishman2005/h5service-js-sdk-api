# h5service

## h5service-yy版本说明

h5service-yy.min.js仅支持webh5，微信小程序。

## 动态

[2019-03-03] 【hummer-channel-sdk新版本】提供h5service-yy.min.js  1.0.0版本发布

（1）new NewH5(thirdUdbAppId: string="", miniAppId: string="", bReLoginAlways: boolean=false, udbAppId: string, udbAppkey: string)

【注】与以前版本兼容。new NewH5 新增参数udbAppId和udbAppkey。

如果不填，默认appname='yymwebh5'；如果填写，请业务填写正确的udbAppId和udbAppkey。

【验收条件】：
	（1）service通道登录成功；
	（2）后端服务统计到预期的appname；


## h5service-yy js-sdk安装配置

（1）npm包

npm install h5service-yy

```javascript
import h5service from 'h5service-yy.min.js'
```
