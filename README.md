# Script

脚本库，来源于网络，仅供学习交流！

## [BoxJS](https://docs.boxjs.app)

[点击验证 BoxJS](http://boxjs.com)

## 中国联通(10010)


## 中国移动(10086)

## 中国电信(10000)


## 中国广电(10099)

https://raw.githubusercontent.com/qnwj-script/Script/refs/heads/main/rewrite/10099.qx.conf

### Quantumult X

```properties
[mitm]
hostname = wx.10099.com.cn

[rewrite_local]
https://wx.10099.com.cn/contact-web/api/busi/qryUserInfo url script-request-body https://raw.githubusercontent.com/qnwj-script/Script/refs/heads/main/script/10099.cookie.js

[task_local]
3 0 * * * https://raw.githubusercontent.com/qnwj-script/Script/refs/heads/main/script/10099.js, tag=ChinaBroadnet, img-url=https://github.com/wuhuhuuuu/study/raw/main/Scripts/ChinaBroadnet/ChinaBroadnet.png
```
