# KeRo AI Prompt Library

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
  <a href="examples/ecommerce-product-copy.md">使用示例</a>
</p>

---

## 这个仓库里有什么

当前仓库包含：

- **9 个主题分类**：市场自动化、翻译润色、文案广告、短视频 TikTok、AI 生图视频、电商视觉、条漫角色、写真修复、电商海报。
- **88 个实用 Prompt**：覆盖从商品文案、TikTok 脚本、AI 生图、视频分镜到电商详情页的常见任务。
- **11 个进阶 Prompt 包**：适合更复杂的电商视觉、视频复刻、Seedance、MJ 摄影、市场日报等工作流。
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
| 做美股日报自动化 | [美股收盘日报自动化](prompts/01-market-automation.md#us-market-daily-report) | 市场日报、事实核验、自动化报告 |

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

## Prompt 文件地图

下面是仓库里的主要 Prompt 分类。你可以从这里进入完整分类文件，也可以直接点具体 Prompt。

### 01 · 市场分析与自动化

- [美股收盘日报自动化](prompts/01-market-automation.md#us-market-daily-report)

适合：金融日报、市场信息整理、需要核验来源的自动化报告。

### 02 · 翻译、音频与文本润色

- [提取音频与双语时间轴](prompts/02-translation-and-polishing.md#extract-audio-bilingual-timeline)
- [视频 / 音频双语翻译](prompts/02-translation-and-polishing.md#audio-video-bilingual-translation)
- [中文转泰语本地化](prompts/02-translation-and-polishing.md#zh-to-th-localization)
- [泰语本地化二次迭代](prompts/02-translation-and-polishing.md#thai-localization-iteration)
- [文本润色：优雅版与口语版](prompts/02-translation-and-polishing.md#text-polishing)

适合：字幕、口播稿、泰语本地化、双语时间轴、中文内容润色。

### 03 · 文案、电商与广告

- [抖音文案角色设定](prompts/03-copywriting.md#douyin-copywriting-role)
- [泰国 TikTok 墨镜文案](prompts/03-copywriting.md#thai-tiktok-sunglasses-copy)
- [通用高质量 Prompt 母模板](prompts/03-copywriting.md#universal-prompt-template)
- [爆款标题](prompts/03-copywriting.md#viral-headlines)
- [小红书种草笔记](prompts/03-copywriting.md#xiaohongshu-post)
- [朋友圈 / 社群短文案](prompts/03-copywriting.md#social-copy)
- [电商详情页文案](prompts/03-copywriting.md#ecommerce-detail-copy)
- [信息流广告 A/B 变体](prompts/03-copywriting.md#feed-ad-ab)
- [15 / 30 / 60 秒短视频脚本](prompts/03-copywriting.md#short-video-15-30-60)
- [品牌 Slogan / 一句话定位](prompts/03-copywriting.md#brand-slogan)
- [二次迭代 Prompt](prompts/03-copywriting.md#prompt-iteration)
- [按需求生成 Prompt](prompts/03-copywriting.md#prompt-generator)

适合：商品文案、广告投放、标题、Slogan、种草笔记、私域文案和 Prompt 二次优化。

### 04 · 短视频与 TikTok 运营

- [短视频脚本创作](prompts/04-short-video-and-tiktok.md#short-video-script)
- [资深短视频编导](prompts/04-short-video-and-tiktok.md#short-video-director)
- [千川高转化短视频编剧](prompts/04-short-video-and-tiktok.md#qianchuan-video-writer)
- [视频转中文知识笔记](prompts/04-short-video-and-tiktok.md#video-to-chinese-notes)
- [TikTok 运营文案审核](prompts/04-short-video-and-tiktok.md#tiktok-copy-review)
- [TikTok 文案审核二次迭代](prompts/04-short-video-and-tiktok.md#tiktok-copy-review-iteration)
- [泰国 TikTok 痛点深挖](prompts/04-short-video-and-tiktok.md#thai-tiktok-pain-points)
- [视频口播文案提取](prompts/04-short-video-and-tiktok.md#spoken-copy-extraction)
- [AI 动漫短剧编剧](prompts/04-short-video-and-tiktok.md#ai-animation-writer)

适合：短视频选题、脚本、镜头、BGM、TikTok 审核、痛点洞察和视频内容提取。

### 05 · AI 生图、视频与分镜

- [图片反向解析 Prompt](prompts/05-image-and-video-generation.md#image-prompt-reverse)
- [图生视频 Prompt 助手](prompts/05-image-and-video-generation.md#image-to-video)
- [视频首尾帧图片 Prompt 助手](prompts/05-image-and-video-generation.md#first-last-frame)
- [Seedance 2.0 场景配置示例](prompts/05-image-and-video-generation.md#seedance-scene-config)
- [电影感绘图 Prompt 改写](prompts/05-image-and-video-generation.md#cinematic-image-prompt)
- [NanoBananaPro 5×5 分镜](prompts/05-image-and-video-generation.md#nanobanana-5x5-storyboard)
- [4×4 产品广告分镜](prompts/05-image-and-video-generation.md#product-ad-4x4-storyboard)
- [图像风格要素分析与原创迁移](prompts/05-image-and-video-generation.md#visual-style-analysis)
- [25 宫格叙事分镜](prompts/05-image-and-video-generation.md#25-grid-storyboard)

适合：AI 绘图、图生视频、首尾帧、电影感画面、产品广告故事板和分镜生成。

### 06 · 电商视觉设计

- [天猫主图详情页设计（Gemini）](prompts/06-ecommerce-visual-design.md#tmall-visual-gemini)
- [天猫主图详情页设计（ChatGPT）](prompts/06-ecommerce-visual-design.md#tmall-visual-chatgpt)

适合：天猫主图、详情页切片、视觉策略、字体排版、底图生成提示词。

### 07 · 条漫、角色与写真

- [两格条漫需求示例](prompts/07-storyboard-and-character.md#two-panel-example)
- [日式儿童搞怪两格条漫导演](prompts/07-storyboard-and-character.md#two-panel-comic-director)
- [人像角色设定卡](prompts/07-storyboard-and-character.md#character-sheet)

适合：条漫分镜、角色设定、人物设定卡和视觉一致性。

### 08 · Banana 人像、写真与修复

- [复古女仆风成年写真](prompts/08-banana-portrait-and-restoration.md#banana-maid-portrait)
- [圣诞兔耳造型成年写真](prompts/08-banana-portrait-and-restoration.md#banana-christmas-portrait)
- [古风夜景人像](prompts/08-banana-portrait-and-restoration.md#banana-ancient-style-portrait)
- [杂志拼贴近景人像](prompts/08-banana-portrait-and-restoration.md#banana-editorial-closeup)
- [极致清晰摄影感人像](prompts/08-banana-portrait-and-restoration.md#banana-crisp-photo-portrait)
- [冷感街头监控拼贴](prompts/08-banana-portrait-and-restoration.md#banana-cold-street-surveillance)
- [鱼眼镜头多姿势重构](prompts/08-banana-portrait-and-restoration.md#banana-fisheye-multipose)
- [手持自拍人像](prompts/08-banana-portrait-and-restoration.md#banana-handheld-selfie)
- [老照片高保真修复（JSON）](prompts/08-banana-portrait-and-restoration.md#banana-photo-restoration-json)
- [老照片高保真修复（中文版）](prompts/08-banana-portrait-and-restoration.md#banana-photo-restoration-zh)
- [韩系氛围感妆容人像](prompts/08-banana-portrait-and-restoration.md#banana-korean-makeup-portrait)
- [清冷临水氛围人像](prompts/08-banana-portrait-and-restoration.md#banana-waterside-portrait)
- [原创卡通毛绒玩偶](prompts/08-banana-portrait-and-restoration.md#banana-original-plush-toy)
- [居家近景人像](prompts/08-banana-portrait-and-restoration.md#banana-home-closeup)
- [场景与人物真实融合](prompts/08-banana-portrait-and-restoration.md#banana-scene-person-blending)
- [怀旧照片分析与重现](prompts/08-banana-portrait-and-restoration.md#banana-vintage-photo-recreation)

适合：成人写真风格、人像风格化、老照片修复、场景融合、原创玩偶和视觉重现。

### 09 · Banana 电商、海报与社交视觉

- [10 屏产品电商 KV 系统](prompts/09-banana-ecommerce-and-poster.md#banana-ecommerce-10-screen-kv)
- [工业级电商详情页启动配置](prompts/09-banana-ecommerce-and-poster.md#banana-ecommerce-launch-config)
- [电商详情页第一阶段分析](prompts/09-banana-ecommerce-and-poster.md#banana-ecommerce-stage-one)
- [海报 01：品牌 LOGO 生成](prompts/09-banana-ecommerce-and-poster.md#banana-poster-logo)
- [海报 02：产品场景展示](prompts/09-banana-ecommerce-and-poster.md#banana-poster-lifestyle)
- [海报 03：多场景拼贴](prompts/09-banana-ecommerce-and-poster.md#banana-poster-collage)
- [偏光墨镜 10 屏中文海报](prompts/09-banana-ecommerce-and-poster.md#banana-polarized-sunglasses-zh)
- [墨镜英泰双语海报系统](prompts/09-banana-ecommerce-and-poster.md#banana-sunglasses-en-th)
- [商业海报 Prompt 生成器](prompts/09-banana-ecommerce-and-poster.md#banana-commercial-poster-generator)
- [职场主题表情贴纸](prompts/09-banana-ecommerce-and-poster.md#banana-workplace-stickers)
- [3×3 高端影棚产品故事板](prompts/09-banana-ecommerce-and-poster.md#banana-3x3-product-storyboard)
- [产品视觉风格自适应](prompts/09-banana-ecommerce-and-poster.md#banana-style-adaptation)
- [产品形态矫正与精修](prompts/09-banana-ecommerce-and-poster.md#banana-product-retouch)

适合：电商海报、产品 KV、墨镜视觉、商业海报、贴纸、产品精修和产品故事板。

## 进阶 Prompt 包

这些文件适合更长、更复杂的工作流，通常不是复制一句就结束，而是按步骤执行。

- [美股收盘日报完整版](prompt-packs/us-market-daily-report.md)
- [美股日报自动化指令](prompt-packs/us-market-automation.md)
- [高端香水广告两步式导演](prompt-packs/luxury-perfume-director.md)
- [视频复刻拆解 v2.1](prompt-packs/video-remake-analysis-v2.1.md)
- [Seedance 2.0 平台 / API 双模式 v4.0](prompt-packs/seedance-platform-api-v4.md)
- [Seedance 2.0 平台版 v4.1](prompt-packs/seedance-platform-v4.1.md)
- [双语 MJ 摄影 Prompt 导演](prompt-packs/bilingual-mj-photo-director.md)
- [AI 杂志摄影 Prompt 导演](prompt-packs/ai-magazine-photo-director.md)
- [工业级 AIGC 电商详情页生成系统 V3.0](prompt-packs/industrial-aigc-ecommerce-v3.md)
- [工业级 AIGC 电商详情页 Prompt Gem V4.0](prompt-packs/industrial-aigc-ecommerce-v4.md)
- [SKU 详情页导演 Skill Lite V1.0（历史版）](prompt-packs/sku-detail-page-director-lite-v1.md)

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
prompts/          按主题分类放 Prompt
prompt-packs/     放复杂长流程 Prompt 包
examples/         放具体使用示例
docs/             放模板、规范、网站规划
.github/          放 issue 和 PR 模板
website/          放第一版静态网站
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

## License 说明

除非文件中另有说明，本仓库的 Prompt、文档、示例和文字内容采用 [Creative Commons Attribution-NonCommercial 4.0 International](LICENSE) 许可。第三方图片、商标、平台名称和工具名称仍归各自权利人所有。

如果这个项目对你有帮助，欢迎给它一个 Star。它会帮助更多人发现这个项目。

---

作者：**秋水 Kero** · X: [@Isonlyonenice](https://x.com/Isonlyonenice)
