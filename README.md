# ZJU Rule Xec

基于 [SubConv/ZJU-Rule](https://github.com/SubConv/ZJU-Rule) 定制的 Clash.Meta 分流规则，用于组合普通代理订阅与 ZJU 专用链路。

项目使用 CC-BY-SA-4.0 协议发布 [![CC-BY-SA-4.0](https://licensebuttons.net/l/by-sa/4.0/88x31.png)](https://creativecommons.org/licenses/by-sa/4.0/deed.zh)


## 支持功能

+ ZJU 内网/学术资源独立分流，支持 `ZJU Connect` 与经它反代的 `ZJU Lab SS`
+ BBY、OKZ 和 ZJU 节点分类，保留 AI 平台、YouTube、Netflix 等详细策略组
+ 订阅广告与公告节点独立归入 `ℹ️ 订阅信息`，不参与手动选择、自动测速、故障转移、负载均衡或地区分组
+ `🚫 禁止访问` 支持通过 `Clash/Ruleset/Entertainment.list` 自定义拦截站点
+ Hello 内网 `10.168.0.0/13` 在 ZJU `10.0.0.0/8` 之前直连
+ 节点自动选择
+ 节点故障转移
+ 节点负载均衡
+ Telegram 分流
+ Youtube 分流
+ Netflix 分流
+ 动画疯分流
+ 哔哩哔哩分流（解锁港澳台）
+ Google 服务分流
+ OneDrive 分流
+ Microsoft 服务分流
+ Apple 服务分流
+ 游戏平台分流（Steam/Epic/Sony）
+ 网易云音乐分流（灰色歌曲解锁）
+ 广告拦截/应用净化/AdBlock/隐私防护
+ 节点分地区管理（香港/日本/美国/台湾/狮城/韩国）
+ ...

## Subconverter 模板

Clash.Meta 使用 [`Clash/config/ZJU.ini`](Clash/config/ZJU.ini)。调用方需在合并订阅时为节点添加 `[BBY]`、`[OKZ]`、`[ZJU]` 来源标记，并将公告类节点额外标记为 `[INFO]`。

## 常见问题

+ 我可以对 ZJU Rule 进行完善吗？

  欢迎通过 Issue 提出意见或建议，或提交 Pull Request 完善规则。通用规则建议优先反馈给上游。
