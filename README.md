## README

UnRaid docker 模板库，目前支持的容器：

|容器|说明|备注|
|---|---|---|
|FileBrowserEnhanced|文件管理| 灯大出品必属精品|
|Frpc| frp 客户端| 没有公网 ipv4 可能需要|
|ddnsgo| 动态ip映射工具| 动态公网 ipv4 可能需要|
|OneDrive| OneDrive Linux 客户端| 开源第三方Linux OneDrive客户端，基于官方提供的Alpine镜像|
|ss-local| Shadowsocks 客户端| Shadowsocks-libev 客户端 |
|baidunetdisk| 百度网盘官方Linux客户端| 支持web网页或VNC访问 |
|qinglong| 青龙面板| 懂的都懂 |
|clash-tproxy|clash-premium|基于Clash实现透明网关|
|yacd|Yet another clash dashboard|clash dashboard|
|simplehttpserver|简易文件服务器|测试用|
|Alist|文件服务|支持多种网盘协议的Web文件服务软件|
|dst-server|游戏|饥荒联机版服务器|
|acmesh|https证书|免费https证书并自动更新|

#### 添加模板库

打开 unraid 的 docker 页面：

1. 将本仓库地址 https://github.com/fengdingwen/unraid 填入 **Template repositories**
2. 点击 **SAVE** 保存，unraid 会自动拉取模板库并刷新页面