# Personal Use Shadowrocket Collection

This repository contains a collection of Shadowrocket rules that I use personally. Most of the configurations are collected from internet. Thanks to original authors.

## Base Routing Rules

| Rule and Source | Description | Link |
|------|-------------|------|
| Built-in Config | Shadowrocket 内置的基本配置。修改 DNS 为 DoH 后可以作为基底使用。 | None |
| [GMOogway/direct](https://github.com/GMOogway/shadowrocket-rules) | 全面的直连域名列表（11w+）。核心上游为 felixonmars/dnsmasq-china-list、v2fly/domain-list-community。 | [Github Raw](https://raw.githubusercontent.com/GMOogway/shadowrocket-rules/master/sr_direct_list.module) |
| [GMOogway/proxy](https://github.com/GMOogway/shadowrocket-rules) | 全面的代理域名列表（2w+）。核心上游为 v2fly/domain-list-community。 | [Github Raw](https://raw.githubusercontent.com/GMOogway/shadowrocket-rules/master/sr_proxy_list.module) |
| [GMOogway/reject](https://github.com/GMOogway/shadowrocket-rules) | 全面的拦截域名列表（16w+）。核心上游为 AdGuard DNS filter。 | [Github Raw](https://raw.githubusercontent.com/GMOogway/shadowrocket-rules/master/sr_reject_list.module) |

## Extended Routing Rules

| Rule and Source | Description | Link |
|------|-------------|------|
| [ckrvxr/anti_pcdn](https://github.com/ckrvxr/shadowrocket_collection) | 屏蔽 PCDN 节点，强制使用优质的传统 CDN，提高加载速度，哔哩哔哩提速效果明显。 | [Github Raw](https://raw.githubusercontent.com/Ckrvxr/shadowrocket_collection/refs/heads/main/source/anti_pcdn.module) |
| [v2fly/category-games@cn](https://github.com/yuumimi/rules) | 让国内有下载服务器的游戏下载走直连，可以节省大量代理节点流量。 | [Github Raw](https://raw.githubusercontent.com/Ckrvxr/shadowrocket_collection/refs/heads/main/source/category-games%40cn.module) |
| [v2fly/apple](https://github.com/yuumimi/rules) | 强制 Apple 域名走代理 | [Github Raw](https://raw.githubusercontent.com/Ckrvxr/shadowrocket_collection/refs/heads/main/source/apple.module) |
| [v2fly/microsoft](https://github.com/yuumimi/rules) | 强制 Microsoft 域名走代理 | [Github Raw](https://raw.githubusercontent.com/Ckrvxr/shadowrocket_collection/refs/heads/main/source/microsoft.module) |


## AD Blocking

| Rule and Source | Description | Link |
|------|-------------|------|
| [deezertidal/startingad](https://github.com/deezertidal/shadowrocket-rules) | 去开屏广告（500+） | [yfamilys Raw](https://yfamilys.com/module/startingad.module) |

## Other Resources

- [deezertidal/shadowrocket-rules](https://github.com/deezertidal/shadowrocket-rules)
- [fmz200/wool_scripts](https://github.com/fmz200/wool_scripts)
- [LOWERTOP/Shadowrocket-First](https://github.com/LOWERTOP/Shadowrocket-First)
- [axtyet/Luminous](https://github.com/axtyet/Luminous)
