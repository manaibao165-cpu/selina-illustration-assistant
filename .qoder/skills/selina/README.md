# Selina (设计师泡泡) - 智能文档配图助手

> **AI-Powered Document Illustration Assistant**

---

## 📖 简介 | Introduction

**设计师泡泡** 是一款专为文档配图而生的 AI 助手。只需提供文档链接，她就能自动分析内容、推荐配图风格，并生成专业的 AI 绘图 Prompt，让你的文档瞬间拥有统一、精美的视觉呈现。

**Selina (Designer Paopao)** is an AI assistant designed specifically for document illustration. Simply provide a document link, and she will automatically analyze the content, recommend illustration styles, and generate professional AI drawing prompts—giving your documents a unified, polished visual presentation instantly.

---

## ✨ 核心功能 | Features

### 1. 多平台文档支持 | Multi-Platform Support
- 钉钉文档 (DingTalk Docs)
- 飞书文档 (Feishu/Lark Docs)
- Notion
- 语雀 (Yuque)
- GitHub Markdown
- 本地 Markdown 文件

### 2. 智能风格推荐 | Smart Style Recommendation
基于文档内容自动推荐最适合的配图风格：

| 风格 | 特点 | 适用场景 |
|------|------|----------|
| **Notion极简编辑风** | 黑白灰，大量留白 | 知识库、产品文档 |
| **Stripe渐变科技风** | 紫蓝渐变，现代感 | SaaS产品、技术文档 |
| **SaaS扁平友好风** | 明亮色彩，圆润图标 | 用户手册、教程 |
| **AI极简抽象高级风** | 深色背景，抽象几何 | AI产品、技术白皮书 |
| **Apple极简产品风** | 纯白背景，产品为中心 | 产品介绍、发布会 |
| **等轴信息图科技风** | 3D等轴视角，层次清晰 | 架构图、流程图 |
| **粘土3D软萌风** | 圆润3D质感，柔和阴影 | 教育内容、轻松主题 |
| **编辑拼贴艺术风** | 混合媒介，艺术感强 | 品牌故事、创意内容 |

### 3. 交互式配置 | Interactive Configuration
- 🌐 **语言选择**: 中文 / English
- 📐 **图片比例**: 16:9 (默认) / 4:3 / 1:1 / 9:16
- 🎨 **风格确认**: AI推荐 + 用户确认

### 4. 专业 Prompt 生成 | Professional Prompt Generation
每个配图位置生成独立的 `.md` 文件，包含：
- 详细的 AI 绘图 Prompt
- 建议的插入位置
- 色彩系统配置
- 构图布局说明

---

## 🚀 快速开始 | Quick Start

### 安装 | Installation

1. 将 `SKILL.md` 复制到你的 Qoder 技能目录：
```bash
# 项目级技能
mkdir -p .qoder/skills/selina
cp SKILL.md .qoder/skills/selina/

# 或全局技能
mkdir -p ~/.qoder/skills/selina
cp SKILL.md ~/.qoder/skills/selina/
```

2. 重启 Qoder 或刷新技能列表

### 使用 | Usage

1. **唤起泡泡**
   ```
   泡泡，帮这篇文档配几张图
   ```

2. **提供文档链接**
   ```
   https://alidocs.dingtalk.com/...
   ```

3. **确认风格配置**
   - 接受 AI 推荐的风格
   - 或从 8 种风格中选择

4. **获取配图方案**
   - 在 `illustrations/prompts/` 目录查看生成的 Prompt
   - 使用 Midjourney / DALL-E / 即梦 等工具生成图片
   - 插入到文档对应位置

---

## 📁 项目结构 | Project Structure

```
selina/
├── SKILL.md           # 核心技能文件 (Core Skill File)
├── avatar-prompt.md   # 头像配置 (Avatar Configuration)
└── README.md          # 本文件 (This File)
```

---

## 🎯 工作流程 | Workflow

```
┌─────────────────┐
│  1. 提供文档链接  │
└────────┬────────┘
         ▼
┌─────────────────┐
│  2. 解析文档内容  │
└────────┬────────┘
         ▼
┌─────────────────┐
│  3. 推荐配图风格  │
└────────┬────────┘
         ▼
┌─────────────────┐
│  4. 配置语言/比例 │
└────────┬────────┘
         ▼
┌─────────────────┐
│  5. 生成Prompt  │
└────────┬────────┘
         ▼
┌─────────────────┐
│  6. 生成图片插入  │
└─────────────────┘
```

---

## 🛡️ 数据安全 | Data Security

- **本地处理**: 所有文档解析和 Prompt 生成本地完成
- **零上传**: 文档内容不会传输到任何外部服务
- **保密原则**: 商业信息、技术细节严格保密

---

## 🤝 贡献 | Contributing

欢迎提交 Issue 和 PR！

1. Fork 本仓库
2. 创建你的特性分支 (`git checkout -b feature/AmazingFeature`)
3. 提交更改 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 打开 Pull Request

---

## 📄 许可证 | License

MIT License - 详见 [LICENSE](LICENSE) 文件

---

## 💬 联系我们 | Contact

- GitHub: [@manaibao165-cpu](https://github.com/manaibao165-cpu)
- 项目地址: https://github.com/manaibao165-cpu/selina-illustration-assistant

---

<p align="center">
  <sub>Designed with ❤️ by 设计师泡泡 (Selina)</sub>
</p>
