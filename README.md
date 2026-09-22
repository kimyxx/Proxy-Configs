# Proxy-Configs

这是一个用于个人学习、测试和资源整理的代理软件配置集合。

本仓库不限定某一种代理软件，后续可以按照软件类型分别整理配置文件。目前已收录 Egern 配置，后续可继续增加 Clash、Surge、Loon、Shadowrocket 等软件的配置。

## 目录结构

```text
.
└── Egern/
    └── Egern.yaml
```

## 当前配置

### Egern

配置文件：[`Egern/Egern.yaml`](Egern/Egern.yaml)

当前配置基于 Repcz 的 Egern 配置进行整理，并增加了独立的 YouTube 和 Gemini 分组：

- `YouTube`：使用 Repcz/EgernRules 中的 YouTube 规则。
- `Gemini`：使用 Repcz/EgernRules 中的 Gemini 规则。
- `AI`、`Google`、`Streaming` 等原有分组继续保留。
- YouTube 和 Gemini 规则放在通用 AI、Google 规则之前，以便优先匹配。

配置中引用的远程规则、模块和图标来自对应的原作者或开源项目。使用前请自行检查远程资源是否仍然有效，并根据自己的节点、软件版本和网络环境进行调整。

## 规则和资源来源

### 核心规则仓库

- [Repcz/Tool](https://github.com/Repcz/Tool)：提供 Egern 配置主体，以及 Direct、Reject、AI、Telegram、Twitter、Facebook、TikTok、Game、Google、Github、Microsoft、Emby、Spotify、Bahamut、Netflix、Disney、PrimeVideo、HBO、Proxy、AppleServers、Lan 等规则。
- [Repcz/EgernRules](https://github.com/Repcz/EgernRules)：提供独立的 [YouTube 规则](https://github.com/Repcz/EgernRules/blob/X/Rules/YouTube/YouTube.yaml) 和 [Gemini 规则](https://github.com/Repcz/EgernRules/blob/X/Rules/Gemini/Gemini.yaml)。

### 配置中引用的其他项目

- [Loyalsoldier/geoip](https://github.com/Loyalsoldier/geoip)：提供 GeoIP 和 ASN 数据库。
- [Koolson/Qure](https://github.com/Koolson/Qure)：提供策略组图标资源。
- [Orz-3/mini](https://github.com/Orz-3/mini)：提供 AI 图标资源。
- [Repcz/Repcz.github.io](https://github.com/Repcz/Repcz.github.io)：提供 Egern 图标资源。
- [QingRex/LoonKissSurge](https://github.com/QingRex/LoonKissSurge)：提供部分 Surge 模块。
- [fmz200/wool_scripts](https://github.com/fmz200/wool_scripts)：提供 `XWebAds.module` 模块。
- [Keywos/rule](https://github.com/Keywos/rule)：提供网易云相关模块。
- [Maasea/sgmodule](https://github.com/Maasea/sgmodule)：提供 YouTube 增强模块。
- [ConnersHua/RuleGo](https://github.com/ConnersHua/RuleGo)：提供广告拦截模块。
- [githubdulong/Script](https://github.com/githubdulong/Script)：提供京东价格相关模块。
- [ChavyWan/chavyleung/scripts](https://github.com/chavyleung/scripts)：提供 BoxJS 重写模块。
- [kokoryh/Sparkle](https://github.com/kokoryh/Sparkle)：提供哔哩哔哩模块。
- [xream/scripts](https://github.com/xream/scripts)：提供网络信息模块。
- [001ProMax/Surge](https://github.com/001ProMax/Surge)：提供 Spotify 模块。
- [sub-store-org/Sub-Store](https://github.com/sub-store-org/Sub-Store)：提供 Sub-Store 相关 Egern 配置入口。

以上来源均为配置文件当前引用的远程项目。远程规则、模块、图标和数据库可能随上游项目变化、迁移或失效，本仓库不保证其长期可用性。

## 使用说明

1. 根据所使用的代理软件进入对应目录。
2. 下载或复制相应配置文件。
3. 在代理软件中导入配置。
4. 根据实际情况修改节点、策略组、规则和模块。

本仓库中的配置不包含代理节点账号、密码或个人凭据。

## 免责声明

本项目涉及的脚本仅用于资源共享和学习研究，不能保证其合法性、准确性、完整性和有效性，请根据情况自行判断。

- 间接使用该项目的任何用户，包括但不限于建立 VPS 或在某些行为违反国家/地区法律或相关法规的情况下进行传播，本项目对于由此引起的任何隐私泄漏或其他后果概不负责。
- 请勿将本项目的任何内容用于商业或非法目的，否则后果自负。
- 如果任何单位或个人认为该项目的脚本可能涉嫌侵犯其权利，则应及时通知并提供身份证明、所有权证明，我们将在收到认证文件后删除相关脚本。
- 对任何脚本问题概不负责，包括但不限于由任何脚本错误导致的任何损失或损害。
- 您必须在下载后的 24 小时内从计算机或手机中完全删除以上内容。

使用本仓库内容即表示您已阅读、理解并同意以上声明。
