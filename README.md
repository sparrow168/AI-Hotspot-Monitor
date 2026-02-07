# 🎯 AI 热点监控工具

## 📖 项目介绍

本项目用于监控 AI 一人公司、超级个体、个人IP打造等热点内容，帮助自媒体创作者快速发现行业动态和选题灵感。

## 🚀 功能特性

- ✅ **多平台热点聚合**：抖音、知乎、B站、华尔街见闻、财联社等
- ✅ **智能关键词过滤**：精准筛选 AI 商业相关热点
- ✅ **微信推送通知**：企业微信实时推送热点资讯
- ✅ **AI 智能分析**：基于 AI 的热点趋势分析
- ✅ **零门槛部署**：GitHub Pages 一键部署

## 📊 监控内容方向

- 🤖 **AI 一人公司**：独立开发者、单干创业
- 💪 **超级个体**：个人工作室、超级创作者
- 🎯 **个人IP打造**：个人品牌、私域流量
- 💰 **AI 商业落地**：AI 赚钱、AI 创业、AI 应用
- 📱 **头部博主**：AI 博主、科技博主、商业博主

## 📁 项目结构

```
AI-HotSpot-Monitor/
├── TrendRadar/              # 热点监控主程序
│   ├── config/
│   │   ├── config.yaml      # 主配置文件
│   │   └── frequency_words.txt  # 关键词配置
│   └── README.md
├── MediaCrawler/            # 深度爬虫工具
├── docs/
│   ├── DEPLOYMENT.md        # 部署指南
│   ├── CONFIGURATION.md     # 配置指南
│   ├── MEDIACRAWLER_SETUP.md # MediaCrawler 安装
│   └── MONITORING.md        # 监控体系
└── README.md                # 本文件
```

## 🚀 快速开始

### 1. Fork 并配置

1. Fork 本仓库到你的 GitHub 账户
2. 配置 GitHub Secrets（企业微信 Webhook、AI API Key 等）
3. 启用 GitHub Pages

### 2. 配置关键词

修改 `TrendRadar/config/frequency_words.txt` 文件，添加你关注的关键词。

### 3. 验证部署

- 访问 `https://你的用户名.github.io/AI-Hotspot-Monitor/`
- 检查微信是否收到推送

## 📚 文档

- [详细部署指南](docs/DEPLOYMENT.md)
- [关键词配置说明](TrendRadar/config/frequency_words.txt)
- [TrendRadar 官方文档](https://sansan0.github.io/TrendRadar/)

## 🔧 技术栈

- **TrendRadar**: 热点监控与 AI 分析
- **MediaCrawler**: 社交媒体数据爬虫
- **GitHub Pages**: 静态页面托管
- **GitHub Actions**: 自动化部署

## 📝 更新日志

### v1.0.0 (2025-02-07)
- ✨ 初始化项目
- 🎯 配置 AI 一人公司、超级个体、个人IP等核心关键词
- 📱 预设抖音、知乎、B站、小红书、华尔街见闻、财联社等监控平台
- 🔔 配置企业微信推送

## 🤝 贡献

欢迎 Issues 和 Pull Requests！

## 📄 许可证

本项目基于 TrendRadar 开源协议。

## 🙏 致谢

- [TrendRadar](https://github.com/sansan0/TrendRadar) - 热点监控工具
- [MediaCrawler](https://github.com/NanmiCoder/MediaCrawler) - 社交媒体爬虫
