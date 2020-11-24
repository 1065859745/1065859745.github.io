# [promtheus-Dingtalk](https://github.com/1065859745/prometheus-DingTalk)
网上也有Prometheus告警到钉钉的插件，但公司的prometheus监控需要先连接vpn，使用网上的钉钉插件时vpn断开后也会发送告警，故网上的插件不能满足需求，当时心血来潮自己写了一个
## 使用说明
将prometheus配置告警到prometheus-Dingtalk的服务上，当prometheus发送告警后可以转发到钉钉；可选的<kbd>-i</kbd>参数可以对VPN主机进行检测，如果vpn断开可以通过可选的<kbd>-m</kbd>参数来向钉钉发送消息
## Node.js版本
master分支
## Go版本
1.1.0分支
# [slice](https://github.com/1065859745/slice)
对切片的扩展，主要有
- 字符串切片中相同的元素只保留一个
- 字符串切片中相邻相同的元素只保留一个
- 插入和切片中不相同的字符串元素
- 判断字符串切片中是否包含某个字符串
- 判断字符串切片中是否存在相同元素
# [httpexec](https://github.com/1065859745/httpexec)
轻松的将某个命令或可执行文件转换成http接口
## 开发过程中遇到的问题
# [image](https://github.com/1065859745/image)
基于百度图像识别接口的App

[项目预览](https://1065859745.github.io/image)
## 开发过程中遇到的问题
- 解决同源策略（跨域）问题
