系统 要求：Ubuntu 14+ / Debian 7+ / CentOS 7 推荐使用Debian 9 免得出现各种BUG

V2ray IPV4安装代码： bash <(curl -s -L https://git.io/v2ray.sh)

V2ray IPV6安装代码：bash <(curl -sL https://scaleya.netlify.com/share/v2ray233_6.sh)

如果你在使用 Telegram 的话，你可以配置一个 Telegram 的专用代理，这样来，在某些情况下你就不需要再开一个代理软件了。

输入 v2ray tg 即可配置 TG 专用代理

配置 Telegram MTProto

安装好 curl 之后再使用脚本安装v2ray , 安装完成后输入v2ray status命令运行状态，两项显示正在运行才是正常的，如果有一项没有运行，请自己检查是否安装正确 ！

然后输入 v2ray restart 重启v2ray, 这时候如果连不上，过半个小时以后再重启一次v2ray

v2ray info 查看 V2Ray 配置信息

v2ray config 修改 V2Ray 配置

v2ray link 生成 V2Ray 配置文件链接

v2ray infolink 生成 V2Ray 配置信息链接

v2ray qr 生成 V2Ray 配置二维码链接

v2ray ss 修改 Shadowsocks 配置

v2ray ssinfo 查看 Shadowsocks 配置信息

v2ray ssqr 生成 Shadowsocks 配置二维码链接

v2ray status 查看 V2Ray 运行状态

v2ray start 启动 V2Ray

v2ray stop 停止 V2Ray

v2ray restart 重启 V2Ray

v2ray log 查看 V2Ray 运行日志

v2ray update 更新 V2Ray

v2ray update.sh 更新 V2Ray 管理脚本

v2ray uninstall 卸载 V2Ray
