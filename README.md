# FlClash 图标库

个人 FlClash / Mihomo 策略组图标合集。

**总计：3306 个图标，分 6 套。**

| 目录 | 数量 | 来源 | 说明 |
|---|---|---|---|
| `color/` | 349 | [Koolson/Qure](https://github.com/Koolson/Qure) `IconSet/Color` | 默认风格，当前配置正在使用 |
| `dark/` | 314 | Koolson/Qure `IconSet/Dark` | 深色风格 |
| `mini/` | 359 | Koolson/Qure `IconSet/mini` | 小尺寸风格 |
| `oasisic/` | 298 | [Hawaiine/Oasisic-Icons](https://github.com/Hawaiine/Oasisic-Icons) | AI 服务图标，按厂商分类（MIT） |
| `lige/` | 1539 | [lige47/QuanX-icon-rule](https://github.com/lige47/QuanX-icon-rule) | 离歌图标包：国家 / 国内软件 / 机场 logo |
| `mihomo/` | 447 | [andongGitHub/mihomo-icons](https://github.com/andongGitHub/mihomo-icons) | mihomo 向图标 |

另有 bgpeer 的 `color/claude_1.png`、`color/douyin_1.png`（由 WebP 转为 PNG）。

## 用法

```yaml
icon: "https://raw.githubusercontent.com/lishiyaa0/FlClash-icons/main/color/Google.png"
```

国内网络可加 gh-proxy 前缀：

```yaml
icon: "https://gh-proxy.com/https://raw.githubusercontent.com/lishiyaa0/FlClash-icons/main/color/Google.png"
```

jsDelivr（有缓存延迟）：

```yaml
icon: "https://cdn.jsdelivr.net/gh/lishiyaa0/FlClash-icons@main/color/Google.png"
```

## 索引

```
https://raw.githubusercontent.com/lishiyaa0/FlClash-icons/main/icons.json
```

`icons.json` 列出全部图标的名称、所属图标集、直链，以及本配置中正在使用的策略组。

## 个人分类图标集

以下 21 个目录来自 [fancha0/my-icons](https://github.com/fancha0/my-icons)，已统一压缩到 ≤256px（体积由 176 MB 降至 45 MB）：

| 目录 | 数量 | 内容 | 目录 | 数量 | 内容 |
|---|---|---|---|---|---|
| `proxy/` | 223 | 代理软件 | `liumeiti/` | 214 | 流媒体 |
| `shejiao/` | 101 | 社交 | `ruanjian/` | 176 | 软件 |
| `guoqi/` | 316 | 国旗 | `emby/` | 45 | Emby |
| `youxi/` | 35 | 游戏 | `jichang/` | 30 | 机场 |
| `jinrong/` | 25 | 金融 | `gouwu/` | 18 | 购物 |
| `ai/` | 17 | AI 服务 | `sousuo/` | 19 | 搜索 |
| `xinwen/` | 15 | 新闻 | `youjian/` | 5 | 邮件 |
| `yinyue/` | 3 | 音乐 | `NAS/` | 3 | NAS |
| `tiezhi/` | 534 | 贴纸 | `katong/` | 188 | 卡通 |
| `shenqibaobei/` | 118 | 神奇宝贝 | `dog/` | 31 | 萌宠 |
| `dibiao/` | 46 | 地标 | | | |

用法同其他目录：

```yaml
icon: "https://raw.githubusercontent.com/lishiyaa0/FlClash-icons/main/proxy/某图标.png"
```

## 致谢与许可

图标版权归各原作者所有。Oasisic-Icons 为 MIT 许可；Qure、离歌图标包、mihomo-icons 未声明开源许可，本仓库仅作个人配置使用，请勿商用。
