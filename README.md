# KrDict Android

**中文** · [English](README.en.md)

基于 [국립국어원 사전 / korean-dict-nikl](https://github.com/spellcheck-ko/korean-dict-nikl) 数据的离线韩语词典 Android 客户端。支持韩/中/英/日多语释义、全文搜索、TTS 发音与界面四语切换。

## 下载

| 文件 | 说明 |
|------|------|
| [krdict.apk](krdict.apk) | 安装包（75.3 MB，含离线词典数据） |

**词条数量：** 默认 [krdict](https://krdict.korean.go.kr/) **54,839** 条；开启 stdict 后共 **410,934** 条

**系统要求：** Android 7.0（API 24）及以上

### 安装

1. 下载 `krdict.apk` 到手机
2. 允许「未知来源」安装（各品牌设置路径略有不同）
3. 点击 APK 完成安装
4. 首次启动会自动解压词典数据库，稍等片刻即可搜索

## 截图

| 搜索首页 | 搜索结果 |
|:---:|:---:|
| ![搜索首页](screenshots/01-home.png) | ![搜索结果](screenshots/02-search.png) |

| 词条详情 | 设置 |
|:---:|:---:|
| ![词条详情](screenshots/03-detail.png) | ![设置](screenshots/04-settings.png) |

## 功能

- **离线查词** — 内置词典数据，首次启动自动解压，无需联网
- **多语搜索** — 支持韩语、中文、英语关键词
- **词条详情** — 词性、语源、活用、中/英/日释义、词组与例句分区展示
- **简化模式** — 详情页可切换为精简释义视图
- **TTS 发音** — 词头、例句与选区均可朗读（需系统韩语语音包）
- **文字选择** — 长按复制、发音或跳转搜索
- **stdict 开关** — 可选是否纳入标准国语大词典（stdict）词条
- **界面语言** — 中文 / English / 日本語 / 한국어 四语切换

## 数据来源

本应用数据来自 [spellcheck-ko/korean-dict-nikl](https://github.com/spellcheck-ko/korean-dict-nikl)，基于韩国国立国语院公开的词典数据（[CC-BY-SA 2.0 KR](https://creativecommons.org/licenses/by-sa/2.0/kr/)）。

- [한국어기초사전 (krdict)](https://krdict.korean.go.kr/)
- [표준국어대사전 (stdict)](https://stdict.korean.go.kr/)

应用内底部 **数据来源: [국립국어원 사전](https://github.com/spellcheck-ko/korean-dict-nikl)** 可跳转至上游仓库。

> 本仓库为国립国语院数据的衍生项目，非官方应用。例句及部分媒体文件的使用限制请参阅上游仓库说明。

## 本仓库内容

```
.
├── README.md
├── README.en.md
├── krdict.apk          # 安装包
└── screenshots/        # 应用截图
```