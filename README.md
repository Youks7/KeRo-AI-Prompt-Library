<h1 align="center">KeRo AI Prompt Library</h1>

面向电商、TikTok 内容、AI 生图、AI 视频、视频分镜、文案生成、本地化翻译和自动化工作流的实用 Prompt 工作流库。

这个仓库不是“随机提示词合集”，而是把我在真实内容生产中用到的 Prompt 按场景整理成可复制、可替换变量、可继续迭代的工作流。你可以把它当成一个 Prompt 工具箱：先找到自己的任务，再复制对应 Prompt，把产品、受众、平台、语言、风格和素材换成自己的内容。

<p align="center">
  <a href="README.md">简体中文</a> ·
  <a href="README_EN.md">English</a> ·
  <a href="README_ZH-TW.md">繁體中文</a>
</p>

<p align="center">
  <a href="prompts/README.md">完整 Prompt 目录</a> ·
  <a href="docs/PROMPT_TEMPLATE.md">Prompt 标准模板</a> ·
  <a href="docs/STANDARDIZED_PROMPTS.md">标准化示例</a> ·
  <a href="docs/IMAGE_REFERENCES.md">图片引用清单</a> ·
  <a href="examples/ecommerce-product-copy.md">使用示例</a>
</p>

---

## 这个仓库里有什么

当前仓库包含：

- **9 个主题分类**：市场自动化、翻译润色、文案广告、短视频 TikTok、AI 生图视频、电商视觉、条漫角色、写真修复、电商海报。
- **87 个实用 Prompt**：覆盖从商品文案、TikTok 脚本、AI 生图、视频分镜到电商详情页的常见任务。
- **9 个当前进阶 Prompt 包和 2 个历史版本**：适合更复杂的电商视觉、视频复刻、Seedance、MJ 摄影、市场日报等工作流。
- **示例图和示例文件**：部分 Prompt 附带正文示例图，`examples/` 里也提供了可读的使用样例。
- **标准模板和贡献规范**：方便后续继续补充、整理和标准化 Prompt。

适合你使用这个仓库的情况：

- 你做跨境电商，需要产品详情页、卖点文案、广告文案、海报提示词。
- 你做 TikTok / 短视频，需要脚本、钩子、分镜、口播提取、文案审核。
- 你做 AI 生图，需要产品图、海报、视觉风格分析、首尾帧、分镜图。
- 你做 AI 视频，需要图生视频 Prompt、Seedance 场景配置、故事板。
- 你做中泰本地化，需要翻译、润色、双语时间轴、泰语表达优化。
- 你想学习 Prompt 工程，需要看完整结构化 Prompt 是怎么写的。

## 先按你的需求找 Prompt

如果你已经知道自己要做什么，直接从下面这张表进入。

| 你的任务 | 建议先看 | 适合场景 |
|---|---|---|
| 写商品详情页文案 | [电商详情页文案](prompts/03-copywriting.md#ecommerce-detail-copy) | 商品卖点、痛点解决方案、FAQ、CTA |
| 写广告投放文案 | [信息流广告 A/B 变体](prompts/03-copywriting.md#feed-ad-ab) | 抖音、快手、微信、百度、Facebook 信息流 |
| 写爆款标题 | [爆款标题](prompts/03-copywriting.md#viral-headlines) | 小红书、短视频、电商标题、广告标题 |
| 写小红书种草笔记 | [小红书种草笔记](prompts/03-copywriting.md#xiaohongshu-post) | 种草笔记、产品体验、关键词和话题标签 |
| 写朋友圈 / 社群短文案 | [朋友圈 / 社群短文案](prompts/03-copywriting.md#social-copy) | 私域、社群、朋友圈、活动提醒 |
| 写品牌 Slogan | [品牌 Slogan / 一句话定位](prompts/03-copywriting.md#brand-slogan) | 品牌定位、产品一句话、短标语 |
| 做 TikTok 墨镜文案 | [泰国 TikTok 墨镜文案](prompts/03-copywriting.md#thai-tiktok-sunglasses-copy) | 泰国市场、墨镜、短视频带货 |
| 写短视频脚本 | [15 / 30 / 60 秒短视频脚本](prompts/03-copywriting.md#short-video-15-30-60) | 商品短视频、口播、剧情脚本 |
| 做更完整的短视频策划 | [资深短视频编导](prompts/04-short-video-and-tiktok.md#short-video-director) | 镜头语言、BGM、标题、分镜表 |
| 写千川高转化脚本 | [千川高转化短视频编剧](prompts/04-short-video-and-tiktok.md#qianchuan-video-writer) | 付费流量、强钩子、快速转化 |
| 审核 TikTok 文案 | [TikTok 运营文案审核](prompts/04-short-video-and-tiktok.md#tiktok-copy-review) | 平台规则、音效、转场、风险提示 |
| 挖泰国 TikTok 用户痛点 | [泰国 TikTok 痛点深挖](prompts/04-short-video-and-tiktok.md#thai-tiktok-pain-points) | 泰国市场、消费心理、痛点洞察 |
| 提取视频口播文案 | [视频口播文案提取](prompts/04-short-video-and-tiktok.md#spoken-copy-extraction) | 从视频里整理时间线和完整口播稿 |
| 图片反推 AI 绘图 Prompt | [图片反向解析 Prompt](prompts/05-image-and-video-generation.md#image-prompt-reverse) | 看图拆风格、构图、光影、内容 |
| 图生视频提示词 | [图生视频 Prompt 助手](prompts/05-image-and-video-generation.md#image-to-video) | 从静态图生成动态视频描述 |
| 生成视频首尾帧 Prompt | [视频首尾帧图片 Prompt 助手](prompts/05-image-and-video-generation.md#first-last-frame) | FLUX、首尾帧、连续画面 |
| 写电影感绘图 Prompt | [电影感绘图 Prompt 改写](prompts/05-image-and-video-generation.md#cinematic-image-prompt) | 英文电影感生图、镜头和摄影机参数 |
| 做产品广告分镜 | [4×4 产品广告分镜](prompts/05-image-and-video-generation.md#product-ad-4x4-storyboard) | 产品广告故事板、角色和环境一致性 |
| 做多宫格叙事分镜 | [25 宫格叙事分镜](prompts/05-image-and-video-generation.md#25-grid-storyboard) | 叙事分镜、Seedance、连续画面 |
| 设计天猫主图和详情页 | [天猫主图详情页设计（ChatGPT）](prompts/06-ecommerce-visual-design.md#tmall-visual-chatgpt) | 主图、详情页、文案、排版、提示词包 |
| 做工业级电商详情页 | [工业级 AIGC 电商详情页 Prompt Gem V4.0](prompt-packs/industrial-aigc-ecommerce-v4.md) | 长流程电商详情页、AIGC 视觉系统 |
| 做 10 屏产品 KV | [10 屏产品电商 KV 系统](prompts/09-banana-ecommerce-and-poster.md#banana-ecommerce-10-screen-kv) | 10 张海报、产品识别、卖点提取 |
| 做商业海报 Prompt | [商业海报 Prompt 生成器](prompts/09-banana-ecommerce-and-poster.md#banana-commercial-poster-generator) | 上传产品图后生成海报设计提示词 |
| 做产品形态矫正和精修 | [产品形态矫正与精修](prompts/09-banana-ecommerce-and-poster.md#banana-product-retouch) | 产品摆正、商业精修、保持结构不变 |
| 做翻译和本地化 | [中文转泰语本地化](prompts/02-translation-and-polishing.md#zh-to-th-localization) | 中泰翻译、泰语本地表达、口语化 |
| 做音视频双语翻译 | [视频 / 音频双语翻译](prompts/02-translation-and-polishing.md#audio-video-bilingual-translation) | 音视频翻译、双语字幕、时间轴 |
| 做美股日报自动化 | [美股日报自动化指令](prompt-packs/us-market-automation.md) | 市场日报、事实核验、定时生成 |

## 最快使用方法

1. 在上面的表格里找到最接近你任务的 Prompt。
2. 点击链接进入对应文件。
3. 展开 Prompt 条目，复制里面的代码块。
4. 把 `{产品}`、`{受众}`、`{平台}`、`{目标}`、`{语言}`、`{风格}` 这类变量替换成你自己的信息。
5. 如果任务涉及商品、图片或视频，把真实产品资料、参考图、脚本、素材说明一起发给 AI。
6. 得到第一版输出后，不要直接发布，继续使用同文件里的迭代类 Prompt 或追加要求进行二次修改。
7. 发布前人工检查事实、版权、平台规则、价格、认证、功效和敏感表达。

一个简单示例：

```text
我要为 TikTok 写一条偏光墨镜短视频文案。

产品：偏光太阳镜
受众：泰国 18 岁以上户外运动用户
平台：TikTok
语言：泰语
语气：自然、直接、有购买引导，但不要夸张
卖点：偏光、适合开车和户外、轻便、五种颜色
注意：UV400、材质、价格必须以我提供的资料为准，不要编造
```

然后选择：

- 文案方向：[泰国 TikTok 墨镜文案](prompts/03-copywriting.md#thai-tiktok-sunglasses-copy)
- 视频脚本方向：[资深短视频编导](prompts/04-short-video-and-tiktok.md#short-video-director)
- 海报方向：[偏光墨镜 10 屏中文海报](prompts/09-banana-ecommerce-and-poster.md#banana-polarized-sunglasses-zh)

## 浏览全部 Prompt

完整的逐项目录统一维护在 [prompts/README.md](prompts/README.md)，这里仅保留分类入口，避免两份目录不同步。

| 分类 | 入口 | 主要内容 |
|---|---|---|
| 01 · 市场分析与自动化 | [打开](prompts/01-market-automation.md) | 美股日报完整版、自动化版本和示例图 |
| 02 · 翻译、音频与文本润色 | [打开](prompts/02-translation-and-polishing.md) | 双语时间轴、中泰本地化、文本润色 |
| 03 · 文案、电商与广告 | [打开](prompts/03-copywriting.md) | 商品文案、广告、标题、Slogan |
| 04 · 短视频与 TikTok 运营 | [打开](prompts/04-short-video-and-tiktok.md) | 脚本、审核、痛点分析、口播提取 |
| 05 · AI 生图、视频与分镜 | [打开](prompts/05-image-and-video-generation.md) | 生图、图生视频、首尾帧、故事板 |
| 06 · 电商视觉设计 | [打开](prompts/06-ecommerce-visual-design.md) | 主图、详情页、视觉策略 |
| 07 · 条漫、角色与写真 | [打开](prompts/07-storyboard-and-character.md) | 条漫导演、角色设定卡 |
| 08 · Banana 人像、写真与修复 | [打开](prompts/08-banana-portrait-and-restoration.md) | 人像、写真、老照片修复、场景融合 |
| 09 · Banana 电商、海报与社交视觉 | [打开](prompts/09-banana-ecommerce-and-poster.md) | 产品 KV、海报、贴纸、产品精修 |

进阶工作流也由完整目录统一维护：[查看当前进阶 Prompt 包](prompts/README.md#进阶-prompt-包) · [查看历史版本](prompt-packs/archive/README.md)。

## 如何正确使用这些 Prompt

### 1. 不要只复制 Prompt，还要提供真实输入

多数 Prompt 需要你补充信息。越具体，输出越稳定。

建议提供：

- 产品名称、类目、价格区间、核心卖点
- 目标用户、年龄、地区、平台
- 语言、语气、风格、禁用词
- 图片、视频、参考链接、已有文案
- 必须保留的信息和不能编造的信息

### 2. 变量要替换成自己的内容

如果你看到 `{product_name}`、`{target_audience}`、`{platform}`、`{tone}`、`{language}`，不要原样发给 AI。应该换成真实信息。

示例：

```text
{product_name} -> 偏光太阳镜
{target_audience} -> 泰国 18 岁以上户外运动用户
{platform} -> TikTok
{tone} -> 自然、直接、有购买引导
{language} -> Thai
```

### 3. 第一版不是终稿

建议至少做三轮：

1. 第一轮：生成初稿。
2. 第二轮：要求 AI 检查夸大、虚假承诺、平台风险和事实不确定点。
3. 第三轮：按你的品牌语气、平台格式和素材限制压缩或改写。

### 4. 产品事实必须自己核验

不要让 AI 替你编造：

- UV400、防蓝光、偏光、材质、认证、产地
- 价格、折扣、库存、销量、用户数量
- 客户案例、测评结果、平台规则
- 医疗、金融、功效类承诺

无法确认的信息应写成“待核实”或直接删除。

## 示例文件

如果你是第一次用这个仓库，可以先看 `examples/`：

- [电商产品文案示例](examples/ecommerce-product-copy.md)
- [TikTok 视频脚本示例](examples/tiktok-video-script.md)
- [AI 产品图生图示例](examples/ai-image-product-photo.md)
- [产品海报 Prompt 示例](examples/product-poster-prompt.md)
- [翻译与本地化示例](examples/translation-localization.md)

如果你想新增 Prompt，请看：

- [Prompt 标准模板](docs/PROMPT_TEMPLATE.md)
- [标准化 Prompt 样板](docs/STANDARDIZED_PROMPTS.md)
- [贡献指南](CONTRIBUTING.md)

## 仓库结构说明

这个仓库按“Prompt 分类、复杂工作流、示例、文档规范”来组织，方便查找和维护。

```text
prompts/               按主题分类放 Prompt，并维护完整目录
prompt-packs/          放当前复杂长流程 Prompt 包
prompt-packs/archive/  放被新版替代的历史版本
examples/              放具体使用示例
docs/                  放模板、标准化样板和图片引用清单
assets/                放正文示例图和仓库展示资源
.github/               放 issue 和 PR 模板
website/               放第一版静态网站
```

新增或整理 Prompt 时建议遵循：

- 用清晰标题说明用途。
- 写明适合谁使用。
- 列出输入变量。
- Prompt 主体放进代码块。
- 提供示例输入。
- 说明预期输出。
- 写出限制、风险和模型使用建议。

## 贡献方式

欢迎你贡献：

- 新 Prompt
- 更好的变量设计
- 更清晰的示例输入
- 英文、泰文或繁体中文翻译
- 过时 Prompt 的修正
- 链接、标题、Markdown 格式修复

提交前请阅读 [CONTRIBUTING.md](CONTRIBUTING.md)。如果你只是想提需求，可以使用 [Prompt Request Issue 模板](.github/ISSUE_TEMPLATE/prompt_request.md)。

## 使用注意事项

- Prompt 是工作模板，不保证任何模型都输出相同结果。
- 涉及金融、平台规则、产品功效、材质、认证、价格、活动时，必须查询最新可靠来源。
- 只上传和改编你有权使用的图片、视频、字体、商标和人物素材。
- 公开发布前请人工检查事实、版权、隐私、安全和平台合规性。
- 第三方图片、品牌、平台和工具名称仍归各自权利人所有。

更多说明见 [NOTICE.md](NOTICE.md)。

## 使用许可

本仓库的 Prompt、文档和示例文字可以用于学习、参考和非商业使用。  
如果你引用或改编本仓库内容，请注明来源并链接回本仓库。

请不要直接搬运本仓库内容进行商业转卖。  
仓库中涉及的第三方图片、商标、平台名称和工具名称，仍归各自权利人所有。

如果这个项目对你有帮助，欢迎给它一个 Star。它会帮助更多人发现这个项目。

---

作者：**秋水 Kero** · X: [@Isonlyonenice](https://x.com/Isonlyonenice)
