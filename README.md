# KeRo AI Prompt Library

面向电商、TikTok、AI 生图、AI 视频、文案生成、本地化翻译和自动化工作流的实用 Prompt 工作流库。

它不是简单堆放提示词，而是按照真实内容生产场景整理 Prompt，让用户可以直接复制、替换变量、快速投入使用。

<p align="center">
  <a href="README.md">简体中文</a> ·
  <a href="README_EN.md">English</a> ·
  <a href="README_ZH-TW.md">繁體中文</a>
</p>

<p align="center">
  <a href="prompts/README.md">浏览全部 Prompt</a> ·
  <a href="docs/PROMPT_TEMPLATE.md">Prompt 标准模板</a> ·
  <a href="examples/ecommerce-product-copy.md">示例文件</a> ·
  <a href="website/">静态网站</a> ·
  <a href="https://github.com/Youks7/KeRo-AI-Prompt-Library/generate">Use this template</a>
</p>

---

## 项目是什么

KeRo AI Prompt Library 是 Kero 持续整理和实测的 AI Prompt 工作流库。它把角色、任务、输入变量、约束、输出格式和迭代方式组织成可复用模板，帮助用户从零散需求进入更稳定的内容生产流程。

当前仓库包含 **9 个主题分类、88 个实用 Prompt、11 个进阶 Prompt 包和 73 张正文示例图**，覆盖电商、短视频、TikTok、本地化翻译、AI 生图、AI 视频、电商视觉和自动化等场景。

## 适合谁

- 跨境电商运营
- TikTok / 短视频内容创作者
- AI 生图用户
- AI 视频和分镜创作者
- 文案、广告和内容生产团队
- Prompt 工程学习者
- 想搭建自己 Prompt 库的独立开发者

## 可以用它做什么

- 生成电商详情页、广告文案、标题、社交媒体文案和品牌 Slogan。
- 生成 TikTok 脚本、短视频分镜、前三秒钩子和文案审核流程。
- 生成产品图、海报、视觉系统和电商 KV 的 AI 生图提示词。
- 生成 AI 视频、首尾帧、Seedance 和多宫格分镜工作流。
- 处理中文、泰语、本地化改写和双语内容整理。
- 基于本仓库模板创建自己的 Prompt 工作流库。

## Prompt 分类

| 分类 | 适用场景 |
|---|---|
| [电商](prompts/03-copywriting.md#ecommerce-detail-copy) | 商品详情页、卖点、FAQ、广告文案、视觉详情页 |
| [TikTok / 短视频](prompts/04-short-video-and-tiktok.md) | 视频脚本、分镜、钩子、文案审核、用户痛点 |
| [AI 生图](prompts/05-image-and-video-generation.md) | 产品图、海报、电影感提示词、视觉风格分析 |
| [AI 视频](prompts/05-image-and-video-generation.md#image-to-video) | 图生视频、首尾帧、Seedance、动态分镜 |
| [文案生成](prompts/03-copywriting.md) | 标题、社交文案、小红书笔记、Slogan、广告 A/B 版本 |
| [本地化翻译](prompts/02-translation-and-polishing.md) | 中泰本地化、双语时间轴、音视频翻译 |
| [自动化工作流](prompts/01-market-automation.md) | 市场日报、资料核验、可重复研究流程 |

[打开完整 Prompt 目录](prompts/README.md)。

## 快速开始

1. 打开 `prompts/` 或 `prompt-packs/`。
2. 找到最接近当前任务的 Prompt。
3. 复制代码块。
4. 替换 `{product_name}`、`{target_audience}`、`{platform}`、`{tone}`、`{language}` 等变量。
5. 把真实产品资料、参考图、目标平台和风格要求一起提供给 AI。
6. 根据输出继续迭代，不要把第一版直接当作终稿。

## 如何复制使用 Prompt

建议先保留 Prompt 的结构，再替换变量和事实信息。涉及产品功效、材质、认证、价格、活动、平台规则时，必须以你能验证的资料为准。

如果你要新增 Prompt，请优先参考 [docs/PROMPT_TEMPLATE.md](docs/PROMPT_TEMPLATE.md)。部分标准化示例见 [docs/STANDARDIZED_PROMPTS.md](docs/STANDARDIZED_PROMPTS.md)。

## 如何基于模板创建自己的 Prompt 库

1. 点击 [Use this template](https://github.com/Youks7/KeRo-AI-Prompt-Library/generate)。
2. 改成自己的项目名称和定位。
3. 保留 `prompts/`、`prompt-packs/`、`examples/`、`docs/` 这类结构。
4. 用统一变量格式 `{variable_name}` 编写 Prompt。
5. 为每个核心 Prompt 补充使用场景、示例输入、预期输出和注意事项。

## 如何贡献

欢迎贡献新的 Prompt、改进已有 Prompt、补充示例、翻译内容、修正格式或报告过时内容。提交前请阅读 [CONTRIBUTING.md](CONTRIBUTING.md)。

## 使用注意事项

- Prompt 是工作模板，不保证任何模型都输出相同结果。
- 产品功效、材质、产地、认证、价格和活动信息必须以真实证据为准。
- 金融、平台规则和模型能力会变化，执行时必须查询最新可靠来源。
- 只上传和改编你有权使用的图片、视频、字体、商标与人物素材。
- 公开发布前请人工检查事实、版权、隐私、安全和平台合规性。

更多说明见 [NOTICE.md](NOTICE.md)。

## License 说明

除非文件中另有说明，本仓库的 Prompt、文档、示例和文字内容采用 [Creative Commons Attribution-NonCommercial 4.0 International](LICENSE) 许可。第三方图片、商标、平台名称和工具名称仍归各自权利人所有。

如果这个项目对你有帮助，欢迎给它一个 Star。它会帮助更多人发现这个项目。

---

作者：**秋水 Kero** · X: [@Isonlyonenice](https://x.com/Isonlyonenice)
