# Banana 电商、海报与社交视觉

覆盖 10 屏电商详情页、产品海报、墨镜视觉、商业海报生成器、表情贴纸与生日涂鸦。

> 所有品牌、参数、尺寸、功效、认证、价格和售后信息必须以真实资料为准。

> 使用方法：展开条目，复制代码块，再根据人物、产品、品牌、平台和画幅替换变量。

<a id="banana-ecommerce-10-screen-kv"></a>

<details>
<summary><strong>10 屏产品电商 KV 系统</strong></summary>

> ⚠️ 只能提取图片中真实可见的信息；无法确认的参数、认证和卖点必须标记为待核实，不得推断成事实。

````text
完整元提示词：
1.任务说明:我需要为我的产品生成一套完整的电商KV视觉系统提示词（10张海报，9:16竖版格式）。

2.基于我给的产品图（女性睡衣），把产品卖点/参数要点梳理出来，然后给我一套统一旗舰店极简KV系统（9:16），最后输出10张详情页的完整提示词（中英双语、干净大气、至少5张细节特写、背景简单、配色高级），请注意每张图的提示词都是完整的，可以直接使用。

•
第一步：产品信息智能提取（如果上传了图片）
请仔细分析我上传的产品图片，自动提取以下信息： ## 自动识别项目：
品牌名称识别   - 从包装/产品上识别品牌LOGO文字   - 识别中文品牌名和英文品牌名   - 提取品牌标志的设计风格（字体、图标、配色）
产品类型判断**   - 识别产品所属类别（服装/食品/电子/美妆/家居/宠物用品等）   - 识别具体产品名称（从包装文字或产品形态判断）   - 识别产品规格（尺寸、容量、重量等）
卖点提取   - 从包装上的文案提取核心卖点关键词   - 从产品图标/认证标识提取卖点（如：有机认证、无添加、进口等）   - 从产品视觉特征推断卖点（如：颜色、材质、工艺）   - 提取数据卖点（如：百分比、含量、时长等）
配色方案分析   - 提取包装主色调（RGB/HEX色值）   - 识别辅助色和点缀色   - 分析配色风格（清新/沉稳/鲜艳/高级等）
设计风格判断   - 识别包装设计风格（极简/复古/可爱/科技/艺术等）   - 识别字体风格（衬线/无衬线/手写等）   - 识别图案元素（水彩/几何/插画/摄影）
目标受众推断   - 根据包装风格推断目标用户群体   - 根据产品类型推断年龄段   - 根据价格定位推断消费层级
产品参数提取   - 从包装文字提取产品规格（净含量/尺码/功率等）   - 提取成分信息/配料表/营养成分   - 提取使用说明/注意事项   - 提取生产日期/保质期/储存方式。
产品细节识别
- 识别产品材质质感（光滑/粗糙/哑光/高光等）
识别产品结构特点（可拆卸/折叠/便携等）
识别包装特色（自封袋/泵头/喷雾/滴管等）
输出格式：
请将识别结果整理为以下格式：
【识别报告】
品牌名称：[中文] / [英文]
产品类型：[大类] - [具体产品]
产品规格：[具体规格]
核心卖点：[卖点1 - 中英文]
[卖点2 - 中英文]
[卖点3 - 中英文]
[卖点4 - 中英文]
[卖点5 - 中英文]
主色调：[颜色名称] (#HEX) + [颜色名称] (#HEX)
辅助色：[颜色名称] (#HEX)
设计风格：[风格描述]
目标受众：[用户画像]
品牌调性：[调性描述]
包装亮点：[特殊设计元素]

第二步：视觉风格选择
基于识别的产品信息，请推荐最适合的视觉风格（也可手动指定）：视觉风格选项
（AI自动推荐或手动选择）
□ 杂志编辑风格（高级、专业、大片感、粗衬线标题、极简留白）
□ 水彩艺术风格（温暖、柔和、晕染效果、手绘质感）
□ 科技未来风格（冷色调、几何图形、数据可视化、蓝光效果）
□ 复古胶片风格（颗粒质感、暖色调、怀旧氛围、宝丽来边框）
□ 极简北欧风格（性冷淡、大留白、几何线条、黑白灰）
□ 霓虹赛博风格（荧光色、描边发光、未来都市、暗色背景）
□ 自然有机风格（植物元素、大地色系、手工质感、环保理念）
AI推荐依据： - 根据产品类型自动匹配最佳风格 - 根据包装设计风格延续品牌调性 - 根据目标受众审美偏好推荐 --

第三步：文字排版效果选择
文字排版效果（AI自动推荐或手动选择）
□ 粗衬线大标题 + 细线装饰 + 网格对齐（杂志风）
□ 玻璃拟态卡片 + 半透明背景 + 柔和圆角（现代风）
□ 3D浮雕文字 + 金属质感 + 光影效果（奢华风）
□ 手写体标注 + 水彩笔触 + 不规则布局（艺术风）
□ 无衬线粗体 + 霓虹描边 + 发光效果（赛博风）
□ 极细线条字 + 大量留白 + 精确对齐（极简风）

第四步：生成完整提示词系统
请严格按照以下要求生成：视觉风格选择（必选其一）
□ 杂志编辑风格（高级、专业、大片感、粗衬线标题、极简留白）
□ 水彩艺术风格（温暖、柔和、晕染效果、手绘质感）
□ 科技未来风格（冷色调、几何图形、数据可视化、蓝光效果）
□ 复古胶片风格（颗粒质感、暖色调、怀旧氛围、宝丽来边框）
□ 极简北欧风格（性冷淡、大留白、几何线条、黑白灰）
□ 霓虹赛博风格（荧光色、描边发光、未来都市、暗色背景）
□ 自然有机风格（植物元素、大地色系、手工质感、环保理念）
# 文字排版效果（必选其一）
□ 粗衬线大标题 + 细线装饰 + 网格对齐（杂志风）
□ 玻璃拟态卡片 + 半透明背景 + 柔和圆角（现代风）
□ 3D浮雕文字 + 金属质感 + 光影效果（奢华风）
□ 手写体标注 + 水彩笔触 + 不规则布局（艺术风）
□ 无衬线粗体 + 霓虹描边 + 发光效果（赛博风）
□ 极细线条字 + 大量留白 + 精确对齐（极简风）
特殊需求（可选）
【是否需要模特】：是 / 否（如果是，描述模特类型）
【是否需要场景】：是 / 否（如果是，描述场景类型）
【是否需要数据可视化】：是 / 否【其他特殊要求】：[如：必须包含产品实物、需要对比图、需要用户评价等] ---
# 生成要求 请严格按照以下结构输出完整提示词系统：
输出结构：
LOGO生成提示词（中英双语，基于识别的品牌设计风格）
海报01 - 主KV视觉（Hero Shot，必须严格还原上传的产品图）
海报02 - 生活场景/使用场景（Lifestyle，展示产品实际使用）
海报03 - 工艺/技术/概念可视化（Process/Concept，基于识别的卖点）
海报04 - 细节特写01（Detail 01，放大产品细节）
海报05 - 细节特写02（Detail 02，材质/质感特写）
海报06 - 细节特写03（Detail 03，功能细节）
海报07 - 细节特写04 或 用户评价（Detail 04 / Review）
海报08 - 品牌故事/配色灵感（Brand Story / Moodboard，使用识别的配色）
海报09 - 产品参数/规格表（Specifications，使用识别的参数）
海报10 - 使用指南/注意事项（Usage Guide，基于产品类型）
````

</details>

<a id="banana-ecommerce-launch-config"></a>

<details>
<summary><strong>工业级电商详情页启动配置</strong></summary>

````text
请基于我上传的这款产品图片，按照这套工业级 AIGC 电商详情页生成系统 V3.0 执行。

平台：淘宝详情页
画幅：750px 宽，9:16 分屏逻辑
产品类目：宠物食品
是否需要中英文双语：是
是否需要模特：否
是否需要场景：是
是否需要数据可视化：是
最终目标：生成 10 屏电商详情页执行蓝图，用于 MJ/SD 生成背景、PS 合成产品、Figma 排版文字。

如果你不知道产品类目，也可以写：

产品类目由你根据图片自动判断。
````

</details>

<a id="banana-ecommerce-stage-one"></a>

<details>
<summary><strong>电商详情页第一阶段分析</strong></summary>

````text
先执行第一阶段：产品识别、真实性分级、类目同质化风险分析、差异化路线推荐。暂时不要输出10屏海报。
````

</details>

<a id="banana-poster-logo"></a>

<details>
<summary><strong>海报 01：品牌 LOGO 生成</strong></summary>

> 示例中的品牌、产品和文案请替换为自己的真实资料。

````text
提示词（中文）： 极简高端时尚品牌logo，矢量风格，干净几何形。品牌名：【"MUYANG"】。图标：细线圆形徽章，内含单支精致叶枝（负空间，现代，优雅）。配色：深苔灰绿色(#2F3A33)搭配温暖米白背景(#F3EFE6)或透明背景。字体：高端衬线体"MUYANG"，字母间距宽松，下方小字"沐阳"。无渐变、无阴影、无3D、无样机、无水印。

01、海报01｜【产品·丝滑睡裙】主KV（Hero）
提示词（中文）： 9:16竖版高端极简时尚海报。柔和摄影棚日光，温暖米白渐变背景（奶油/燕麦色），超干净。精致亚洲美女模特(25-30岁)，精致五官，自然裸妆，长发慵懒随意，放松优雅姿态，全身照，一只手轻轻抚摸裙摆。
服装必须与上传的产品参考图匹配：香槟色/奶油色缎面短款吊带睡裙，细吊带，V领，裙长至大腿中部，丝滑光泽面料，保持服装设计与参考图完全一致。
排版布局：左上角放置MUYANG logo(小号)。顶部居中巨大衬线标题(2行)："SILK SLIP DRESS" / "丝滑睡裙"(中英堆叠，干净)。左侧中部玻璃拟态信息卡(3个要点，双语)：仿真丝触感 / Silk-like touch；修身不紧绷 / Flattering fit；居家也优雅 / Elegant at home。右下角【圆角药丸CTA】："立即选购 → / SHOP NOW →"。
负面词：cluttered, busy, multiple patterns, gradients, shadows, watermark, logo repeated, messy text, low quality, blurry, plain face, unattractive
````

</details>

<a id="banana-poster-lifestyle"></a>

<details>
<summary><strong>海报 02：产品场景展示</strong></summary>

````text
提示词（中文）： 9:16竖版，电影质感干净时尚摄影。背景：柔和晨光透过白色纱帘的卧室，奶白色床品，极简北欧风格，温暖氛围。精致亚洲美女模特全身侧身站立，长发披肩，回眸微笑，一只手撩起发丝。使用上传的产品参考图保持香槟色短款吊带睡裙的形状、长度、面料光泽完全一致。
文字：左上角小号MUYANG logo。左上小号优雅字体："晨光私语 / Morning Whisper"。左下大标题："慵懒的刚刚好"。标题下副标题(双语)："丝滑触肤，开启美好一天 / Silky touch, beautiful day begins."。右下角CTA药丸："了解更多 → / LEARN MORE →"。
负面词：cluttered, busy, dark, messy room, shadows, watermark, messy text, low quality, blurry, plain face
````

</details>

<a id="banana-poster-collage"></a>

<details>
<summary><strong>海报 03：多场景拼贴</strong></summary>

````text
提示词（中文）： 9:16竖版极简拼贴海报，圆角照片块和充足负空间。背景：温暖奶油色，干净。创建4个圆角框展示同一位精致亚洲美女模特穿着上传参考图中相同的香槟色短款吊带睡裙，不同居家场景：清晨卧室窗边、客厅沙发慵懒坐姿、浴室镜前、阳台藤椅喝咖啡。所有框架中保持服装、模特完全一致。
左上角MUYANG logo。底部大衬线标题："一裙多场景"。底部副标题(双语)："居家、约会、度假都适合 / Home, date, vacation ready."。右下角附近添加小型3点列表：不挑场合 / Versatile style；秒变氛围感 / Instant chic；舒适又迷人 / Cozy yet alluring。
负面词：cluttered, busy, multiple patterns, shadows, watermark, messy text, low quality, blurry, plain face
````

</details>

<a id="banana-poster-fabric-sheen"></a>

<details>
<summary><strong>海报 04：面料光泽细节</strong></summary>

````text
提示词（中文）： 9:16竖版高端微距细节海报。背景：奶油色渐变，大量干净负空间。极近距离拍摄上传参考图中缎面面料的光泽质感，展示丝滑反光效果和柔软垂坠感，面料随身体曲线自然流动。左上角MUYANG logo。
右侧大标题(双语)："仿真丝光泽 / Silk-like Sheen"。小文案(双语，2行)："触感细腻，像第二层肌肤 / Delicate touch, like second skin."。"自然反光更显质感 / Natural luster, premium feel."。右下角CTA药丸："了解更多 → / LEARN MORE →"。
负面词：cluttered, busy, multiple patterns, shadows, watermark, messy text, low quality, blurry
````

</details>

<a id="banana-poster-strap-collarbone"></a>

<details>
<summary><strong>海报 05：吊带与肩颈细节</strong></summary>

````text
提示词（中文）： 9:16竖版极简细节海报。背景：温暖米白，超干净。特写拍摄精致亚洲美女模特的锁骨、肩颈线条和细吊带，来自上传参考(精致优雅)，柔和侧光勾勒轮廓，高级质感。添加一个小圆角内嵌图展示完整着装轮廓(非常小，低不透明度)。
左上角MUYANG logo。居中大衬线标题："细吊带设计"。3个微型要点(双语)：展现优美肩颈 / Flatters shoulders；精致不累赘 / Delicate refined；性感而优雅 / Sexy yet elegant。CTA药丸："立即选购 → / SHOP NOW →"。
负面词：cluttered, busy, multiple patterns, shadows, watermark, messy text, low quality, blurry, plain face
````

</details>

<a id="banana-poster-v-neckline"></a>

<details>
<summary><strong>海报 06：V 领剪裁细节</strong></summary>

````text
提示词（中文）： 9:16竖版时尚细节海报，干净摄影棚灯光。背景：淡燕麦到奶油色渐变，无纹理。近距离拍摄V领剪裁细节(从上传参考)，展示领口线条流畅性和恰到好处的深度，性感不失优雅。左上角MUYANG logo。
左侧大标题："V领剪裁"。副标题(双语)："修饰脸型，拉长颈部线条 / Face-flattering, neck-elongating."。添加小标签行："DETAIL 03"(小号)。CTA药丸："了解更多 → / LEARN MORE →"。
负面词：cluttered, busy, multiple patterns, shadows, watermark, messy text, low quality, blurry
````

</details>

<a id="banana-poster-hemline-drape"></a>

<details>
<summary><strong>海报 07：裙摆垂坠细节</strong></summary>

````text
提示词（中文）： 9:16竖版高端细节海报。背景：极浅香槟金雾霾色，低对比。拍摄精致亚洲美女模特侧面下半身，展示短裙裙摆自然垂坠在大腿中部的优美曲线(从上传参考)，面料随身体动态流动，修饰腿部线条。
左上角MUYANG logo。右侧标题(双语)："短款更显腿长"。小文案(双语)："恰到好处的长度，修饰比例 / Perfect length, flattering proportion."。
负面词：cluttered, busy, multiple patterns, shadows, watermark, messy text, low quality, blurry, plain face
````

</details>

<a id="banana-poster-color-model"></a>

<details>
<summary><strong>海报 08：产品配色与型号</strong></summary>

````text
提示词（中文）： 9:16竖版极简时尚情绪板。背景：温暖奶油色。左侧：全身精致亚洲美女模特穿着上传参考图中的香槟色短款吊带睡裙(干净摄影棚，自然站姿)。右侧：整齐排列受睡裙启发的配色/材质色卡(香槟金、奶油色、珍珠白、柔和米色) + 极简线条图标(月亮、羽毛、丝绸、晨露)。保持一切扁平、高端，不繁忙。
左上角MUYANG logo。顶部大衬线："配色灵感 / COLOR INSPIRATION"。3个要点(双语)：香槟金显气质 / Champagne exudes elegance；温柔色更衬肤 / Soft tones flatter skin；低调奢华感 / Subtle luxury。CTA："了解更多 → / LEARN MORE →"。
负面词：cluttered, busy, multiple patterns, shadows, watermark, messy text, low quality, blurry, plain face
````

</details>

<a id="banana-poster-size-spec"></a>

<details>
<summary><strong>海报 09：产品尺码与参数</strong></summary>

````text
提示词（中文）： 9:16竖版极简尺码指南海报。背景：温暖米白，干净。将尺码表(S/M/L)放置为整洁的网格卡片(玻璃拟态，圆角)。内容(双语标题)："尺码参考 / SIZE GUIDE"。表格列：尺码 Size｜衣长 Length｜胸围 Bust｜腰围 Waist｜臀围 Hip。行：S｜90cm｜80-84cm｜64-68cm｜88-92cm；M｜92cm｜84-88cm｜68-72cm｜92-96cm；L｜94cm｜88-92cm｜72-76cm｜96-100cm。左上角MUYANG logo。底部小注释(双语)："手工测量，误差±2cm属正常 / Hand-measured, ±2cm variance normal."。底部贴心提示："建议参考胸围选择尺码 / Suggest sizig by bust measurement."
负面词：no extra patterns, no clutter, no watermark
````

</details>

<a id="banana-poster-trust-page"></a>

<details>
<summary><strong>海报 10：质保、售后与说明</strong></summary>

````text
提示词（中文）： 9:16竖版高端护理海报。背景：奶油色渐变，非常干净。
左上角MUYANG logo。大标题："洗护指南 / CARE GUIDE"。使用5个极简图标 + 简短双语行(干净，不拥挤)：建议手洗或使用洗衣袋 / Hand wash or use laundry bag；冷水或30°C以下水温 / Cold or below 30°C water；不可漂白或强力拧干 / No bleach or wringing；悬挂阴干，避免暴晒 / Hang dry, avoid direct sun；低温熨烫，垫布熨烫更佳 / Low heat iron, use cloth。底部添加小字(双语)："悉心呵护，延长丝滑寿命 / Care well, silkiness lasts longer."。
负面词：no clutter, no heavy texture, no watermark
````

</details>

<a id="banana-polarized-sunglasses-zh"></a>

<details>
<summary><strong>偏光墨镜 10 屏中文海报</strong></summary>

> ⚠️ 偏光、UV400、材质、型号等产品宣称必须有真实证据后才能使用。

````text
全局统一规则
视觉风格（统一10张）：杂志编辑风格（高级、专业、大片感、粗衬线标题、极简留白）
文字排版效果（统一10张）：粗衬线大标题 + 细线装饰 + 网格对齐（杂志风）
LOGO位置统一：左上角（所有海报一致）
CTA按钮统一：右下角药丸按钮，文字“立即选购 SHOP NOW →”（如需纯中文可改为“立即选购 →”）
产品图还原核心要求：必须严格还原上传的产品图，包括镜框形状比例、镜片颜色/镀膜效果、材质质感、LOGO位置与刻字、结构细节等；不得改款、改色、改字。

LOGO生成提示词（中文）
生成一个高端偏光墨镜品牌LOGO，品牌名：[品牌中文]，英文名可选：[BRAND]。整体风格：杂志编辑风、极简高级。LOGO以文字为主（可选极简图标），字体偏高对比衬线或几何无衬线二选一（更推荐高对比衬线，时尚感强）。配色：主色深黑#111111，辅色金属银灰#B8BDC5（少量点缀）。图标（可选）：极简“光线折射/偏振滤光片”抽象符号，线条极细、干净。输出：透明背景，提供横版与竖版两套组合，字距精致，视觉重心稳定。

通用负面词（Negative Prompts）
cluttered, busy, messy layout, unreadable text, typo, garbled letters, watermark, extra logos, duplicated logo, wrong brand, wrong model text, incorrect Chinese, low quality, blurry, overexposed, harsh shadows, cheap poster, plastic look, fake reflections, distorted frame, asymmetrical sunglasses, broken hinge, wrong lens tint, altered coating, changed shape, cartoon, anime, illustration, random accessories
（负面词 / Negative:   cluttered, busy, multiple patterns, harsh shadows, watermark, logo repeated, messy text, low quality, blurry, artificial, plastic-looking, cartoon, anime style, wrong packaging design, different colors, modified logo, changed text, simplified design）

海报01 - 主KV视觉（Hero Shot，必须严格还原上传的产品图）
9:16竖版高端商业海报，杂志编辑风格，极简留白、大片感棚拍。背景为干净无缝浅灰到暖白渐变（#F4F4F4→#FFF7F0），柔和但清晰的侧上方主光+轻微轮廓光，形成高级高光与细腻阴影。
画面中心：偏光墨镜产品静物主角，30–45°角度摆放，镜片朝向观众，镜框边缘有精致反光，材质真实（哑光/高光/金属拉丝/板材纹理必须正确）。镜片反射自然不过曝，克制体现“偏光减眩光”的效果（路面/水面反光被压制的隐喻表现，真实不夸张）。镜片呈现高清高透观感：可隐约看清镜片后方的眼部轮廓或背景细节（体现“看得清里面”，但保持真实不过度透明）。
产品展示（严格还原上传图片，硬性约束）：
•
严格还原上传的产品图：镜框形状比例、镜片颜色/镀膜效果、镜框材质质感、LOGO位置与文字内容、刻字、铰链结构、鼻托形态、镜腿弯曲、所有细节不得改动。
•
产品外观必须与参考图完全一致，不得改变镜框/镜片配色、镀膜渐变、品牌元素、任何文字与标识。
````

</details>

<a id="banana-sunglasses-en-th"></a>

<details>
<summary><strong>墨镜英泰双语海报系统</strong></summary>

> ⚠️ 偏光、UV400、材质、型号等产品宣称必须有真实证据后才能使用。

````text
生成要求 - 完整提示词系统 (英泰双语版)

#提示词内任何内容都做修改，改成适合自己的产品内容的提示词文案

全局设置 (Global Settings)
•
视觉风格： 杂志编辑风格 (Magazine Editorial)
•
文字排版： 泰文大标题 + 英文副标题 (Thai Headline + English Subtitle)
•
双语排版格式：
◦
标题： 泰文在上（大号字体），英文在下（中号无衬线字体）。
◦
说明： 泰文/英文 使用斜杠 "/" 分隔。
海报01｜主KV·无畏强光 (Hero Shot)
设计意图： 直击泰国高日照痛点，强调“不惧强光”。
•
提示词 (中文描述): 9:16竖版，泰国高端时尚杂志风格。极度清晰的自然强光。 画面中心： DUTAI H1005 太阳镜（黑色哑光框，冰蓝镀膜镜片）悬浮在深色火山岩之上，背景是泰国普吉岛风格的碧蓝大海和刺眼阳光。光线虽然强烈，但透过镜片的感觉是清凉的。 文字内容（泰英双语）：
◦
顶部大标题："ท้าทุกแสง" (泰文：挑战每一道光 / Fear No Light)
◦
副标题："FEAR NO GLARE"
◦
右下角卖点："กันยูวี 400 / UV400 PROTECTION" (防UV400)
•
Negative: wrong characters, chinese text, distorted text, messy background, low resolution.
•
Prompt (English for Generation): 9:16 vertical magazine editorial shot, Thailand beach vibe. Intense natural sunlight, high contrast. Subject: Floating DUTAI H1005 Sunglasses (Matte black frame, Ice Blue polarized lenses, yellow "Polarized" tag) above a dark texture rock. Background: Sparkling turquoise Andaman sea and harsh sun. Typography (Thai & English):
◦
Top Center (Stacked): Large Thai Text "ท้าทุกแสง" (Bold Serif) over English Text "FEAR NO GLARE" (Sans-serif).
◦
Bottom Right: Small text "กันยูวี 400 / UV400 PROTECTION".
海报02｜生活场景·驾驶/垂钓 (Lifestyle)
设计意图： 展示佩戴效果，强调高清视野。
•
提示词 (中文描述): 9:16竖版。一位30岁的泰国/亚洲男性，肤色健康小麦色，穿着户外防晒衣，正在驾驶皮卡车或在海边垂钓。阳光直射，但他佩戴着 DUTAI H1005，表情轻松自信。 文字内容（泰英双语）：
◦
中部标题："ภาพคมชัดระดับ HD" (泰文：HD级清晰画面)
◦
英文副标："HD POLARIZED VISION"
````

</details>

<a id="banana-commercial-poster-generator"></a>

<details>
<summary><strong>商业海报 Prompt 生成器</strong></summary>

> 模型版本和文字生成能力可能变化，使用时请根据当前平台能力调整。

````text
#国际顶尖平面设计师你是一位国际顶尖平面设计师，拥有20年专业经验，精通海报设计、平面排版、字体设计、色彩搭配和视觉传达。你的专长包括电商促销、产品推广等商业海报设计、能根据产品特性精准推荐风格、版式、文案及视觉元素。现在，你需要帮助用户生成一个用于即梦AI图片3.0模型（垫图功能）的提示词（称为提示词A)。该提示词A需详细描述海报的色调、氛围、版式、标题设计等，以便模型基于用户上传的白底产品图生成完整海报。
*#任务流程1.引导用户上传图片
－首先，回复用户:“请上传一张照片。我会分析照片特征并设计海报。”
－等待用户上传图片。
2.分析产品图并生成设计建议
－解析上传的产品图：识别照片风格、颜色、形状、材质及潜在受众。
－基于专业设计知识，提供初步建议：
··风格··推荐海报整体风格（如现代简约、复古手绘、可爱清新、科技感等）。
··色调与氛围··建议主色调、点缀色及氛围（如活泼、温馨、高端)。
··版式··规划主体位置(如居中、偏移)、文案区域布局(如对称、层次感)。
··文案设计···
－主标题：建议文案内容、位置（如顶部中央)、字体（如粗体无衬线)
－副标题：建议内容、位置（如右上角)、字体{如简约清晰)、字号（如中等)。
－辅助文案：建议标签文字等，包括位置和宇体。
··其他元素··背景点缀（如几何图形、二维码）、图标等。
－输出建议供用户参考，例如：“分析照片后，我推荐清新可爱风格，主色调蓝色，搭配黄色点缀。主标题可强调产品趣味性，副标题标注适用人群。”
3.生成最终提示词A:
·综合设计建议和照片特征、生成完整的提示词A。
··提示词A格式要求…
－以“海报设计”开头。
－包含：色调、氛围、风格、版式描述。
－详细指定：主标题（文案、位置、字体、字号)、副标题（文案、位置、字体、字号)
－添加背景元素、图标等细节。
－语言简洁专业、类似以下示例:
··plaintext海报设计，潮流海报风格，青春女性模特，戴绿色棒球帽，身着墨绿色连帽开衫外套与简约内搭、浅色系下装，随性倚靠，背景浅素带颗粒质感。主标题是“BREIKEREE’采用粗体无衬线字体，位于画面中央，人物背后：副标题为“2025.06”，位于右上角，字体清晰，字体为无衬线印刷体，简洁明了。旁边配有英文词汇增强趣味性。构图层次分明，主体突出，整体视觉效果吸人且富有吸引力。
##输出规则
－用户上传图片后，先输出设计建议(1-2句话)，询问用户是否调整。
－用户确认后，输出最终提示词A(纯文本格式，可直接复制到即梦AI)。
````

</details>

<a id="banana-workplace-stickers"></a>

<details>
<summary><strong>职场主题表情贴纸</strong></summary>

````text
制作属于自己的专属职场打工牛马表情贴纸 [主体描述], [表情动作], [配饰道具],
3D character design, blind box style, original designer blind-box toy aesthetic,
C4D, Octane render, clay texture, matte finish, soft lighting,
sticker sheet layout, 3x3 grid view,
9 different expressions: happy making heart gesture, sad with tears,
angry with steam, sleepy yawning, surprised with open mouth,
shy blushing, cheering with fist, confused thinking, celebrating with confetti,
each with cute text label in Chinese,
white outline, die-cut, white background,
high quality, 8k --ar 3:4
````

</details>

<a id="banana-birthday-doodle-original"></a>

<details>
<summary><strong>生日涂鸦纪念图（初始版）</strong></summary>

````text
主体呈现:中心人物(参考图)需完整露出，面部无遮挡;涂鸦元素环绕主体分布，且不覆盖人物面部，涂鸦线条为手绘风格，颜色选白色、黄色、粉色。

图案选择:包含生日主题图案(小蛋糕、蜡烛、气球、星星、爱心、彩带、礼物盒)与特殊元素(红包、元宝、金条、钞票雨、招财猫)，另有装饰线条(波浪线、虚线、闪光点、小花朵、箭头)。

文字设计:主标题:“HappyBirthday{姓名}!"，采用手写涂鸦体，置于底部且为大字。

日期标记:"{生日日期}”，风格随性涂鸦，数字略带弧度，放在顶部。

祝福文字:左右两侧各4-6行，均竖向排列;关键词(如“暴富”“上岸”发大财”)用更大字号(普通文字1.5-2倍)+彩色(黄色/粉色)强调;每行文字大小不完全一致，文字略带倾斜、旋转，部分字跳跃式排列。

核心风格要求:笔触:如马克笔/粉笔在照片上直接涂写的感觉，粗细不均匀，边缘略有毛边，非平滑电脑字体。

字迹:有不完美感(略有歪斜、大小不一、间距不等，似真人随手写)，部分笔画自然连笔，非一笔一划分开。

力度:笔画起笔轻、中间重、收笔轻，有手写力度感;字形圆润饱满，转角带弧度，非棱角分明。

细节:部分字的点/撇用小爱心或小星星替代。

色彩搭配:主色为白色手绘线条，点缀色为柔和黄色、粉色、浅蓝色高光，强调色为黄色/粉色(用于部分文字)。整体氛围:轻松、温馨、欢庆，符合小红书/Instagram风格生日帖子美学，且必须是真实手写涂鸦风格，非电脑字体。
````

</details>

<a id="banana-birthday-doodle-v1"></a>

<details>
<summary><strong>生日涂鸦纪念图（迭代 1）</strong></summary>

````text
(杰作, 高画质:1.2), (基于原图添加手绘涂鸦),
保持中心人物面部清晰, (面部无遮挡:1.4),
涂鸦元素环绕主体, (手绘风格:1.3), (马克笔笔触), (粉笔质感),
杂乱的线条, 粗细不均, 边缘毛糙, (白色, 黄色, 粉色),
(生日主题: 小蛋糕, 蜡烛, 气球, 星星, 爱心, 彩带, 礼物盒),
(财富元素: 红包, 金条, 元宝, 招财猫, 飞舞的钞票:1.2),
装饰性线条, 波浪线, 虚线, 闪光点, 小花朵, 箭头,
(排版设计: 底部巨大的英文涂鸦主标题, 顶部手写数字日期, 两侧竖向排列的文字专栏),
文字大小不一, 倾斜旋转, 跳跃式排列,
(关键词高亮: 黄色和粉色的粗体字块),
轻松, 温馨, 欢庆氛围, 小红书风格, Instagram美学,
柔光, 景深

反向提示词：
(涂鸦遮挡面部:1.5), (脸上有字:1.5),
低质量, 模糊, 丑陋,
电脑字体, 矢量图, 呆板的线条,
黑暗风格, 恐怖,
真实的物体(指涂鸦变成了真实的照片物体), 3D渲染
````

</details>

<a id="banana-birthday-doodle-v2"></a>

<details>
<summary><strong>生日涂鸦纪念图（迭代 2）</strong></summary>

````text
上传参考图让大香蕉识别后生成

(杰作, 最佳画质:1.2), (基于图一添加手绘涂鸦层),
(中心人物面部无遮挡:1.5), 人物面部保持原样,
(整体风格: 小红书生日海报风格, 涂鸦艺术, 手账拼贴感),
参考图片涂鸦风格为图二
/* --- 色彩与笔触 --- */
(笔触质感: 马克笔手绘, 粉笔画, 边缘粗糙, 墨水晕染),
(主色调: 白色线条), (点缀色: 荧光黄, 嫩粉色, 奶油蓝),

/* --- 顶部区域 --- */
(顶部排版: 巨大的手写数字 "To {年龄}岁", "{生日日期}", 带有弧度的文字排列),

/* --- 底部区域 --- */
(底部排版: 巨大的英文涂鸦 "HappyBirthday{姓名}!", 粗体, 甚至有重影效果),

/* --- 两侧文字栏 (核心排版) --- */
(布局: 左右两侧密集的竖向文字列),
(字体: 潦草的手写中文, 歪歪扭扭, 大小不一),
(关键词高亮: "暴富", "上岸", "发大财", "自由", "浪漫"),
(高亮词样式: 字体放大2倍, 荧光笔涂抹背景, 醒目),

/* --- 装饰元素 --- */
(图案填充: 生日蛋糕, 蜡烛, 气球, 礼物盒, 招财猫, 金元宝, 飞舞的钞票:1.2),
(细节线条: 波浪线, 虚线, 闪光星芒, 小箭头指向人物, 小爱心符号),

轻松, 欢庆, 拥挤而温馨的构图, 景深, 柔光

反向提示词：
(涂鸦遮挡面部:1.5), (脸上有字:1.5),
(标准的电脑字体), 印刷体, 黑体, 宋体,
文字排版整齐,
低质量, 模糊, 错误拼写, 缺笔少画,
恐怖, 黑暗, 真实物体(指涂鸦变成了真实的照片物体而不是画)
````

</details>

---

[返回 Prompt 目录](README.md) · [返回项目首页](../README.md)
