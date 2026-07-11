# Standardized Prompt Samples

These samples organize representative prompts from `prompts/` and `prompt-packs/` using the shared structure in [PROMPT_TEMPLATE.md](PROMPT_TEMPLATE.md). They are not meant to replace every original prompt at once. They provide a clear pattern for future standardization.

## E-commerce Product Detail Copy

Source: [prompts/03-copywriting.md](../prompts/03-copywriting.md#ecommerce-detail-copy)

### Use Case

Generate structured product detail-page copy for an e-commerce listing.

### Best For

- E-commerce operators
- Product page writers
- Ad and conversion copywriters

### Input Variables

- `{product_name}`
- `{target_audience}`
- `{price_range}`
- `{selling_points}`
- `{proof_points}`
- `{tone}`

### Prompt

```text
You are a practical e-commerce copywriter.

Task: Generate product detail-page copy for {product_name}.

Audience: {target_audience}
Price range: {price_range}
Selling points: {selling_points}
Proof points: {proof_points}
Tone: {tone}

Output:
1. One main selling point within 18 Chinese characters or 12 English words.
2. Three pain-point and solution pairs.
3. Five short selling points.
4. Parameter/specification copy based only on provided facts.
5. Three usage scenarios.
6. Six FAQ items.
7. Two CTA versions: soft and conversion-focused.

Rules:
- Do not invent claims, certifications, prices, or results.
- Mark missing facts as "to be verified".
- Keep copy clear, specific, and ready for layout.
```

### Example Input

```text
product_name: polarized sunglasses
target_audience: outdoor sports users and drivers
price_range: under 100 THB
selling_points: polarized lens, lightweight frame, five color options
proof_points: product photos and supplier specification sheet
tone: persuasive but not exaggerated
```

### Expected Output

A detail-page copy draft with headline, pain-point table, selling points, specification text, scenarios, FAQ, and CTA.

### Notes

Verify UV, polarization, material, and certification claims before publishing.

## TikTok Short Video Script

Source: [prompts/04-short-video-and-tiktok.md](../prompts/04-short-video-and-tiktok.md#short-video-director)

### Use Case

Create a short-form product video script with hook, scene planning, and platform-specific copy.

### Best For

- TikTok creators
- Short-video directors
- E-commerce content teams

### Input Variables

- `{product_name}`
- `{platform}`
- `{target_audience}`
- `{core_selling_point}`
- `{video_style}`
- `{cta}`

### Prompt

```text
You are a senior short-video director who understands {platform} content behavior.

Task: Create a short video script for {product_name}.

Audience: {target_audience}
Core selling point: {core_selling_point}
Video style: {video_style}
CTA: {cta}

Output:
1. Audience psychology analysis.
2. Three title or caption options.
3. A shot-by-shot script table with:
   - Time
   - Shot size / camera movement
   - Visual
   - Dialogue / caption
   - Props / BGM notes
4. Three alternative first-three-second hooks.

Rules:
- Start with a strong visual or pain-point hook.
- Show the product naturally.
- Avoid unverifiable promises and exaggerated claims.
```

### Example Input

```text
product_name: lightweight polarized sunglasses
platform: TikTok
target_audience: Thai outdoor sports users
core_selling_point: comfortable outdoor vision
video_style: fast, bright, product-focused
cta: check the product link
```

### Expected Output

A shooting-ready table with hook, scene flow, product proof, and CTA.

### Notes

Review local platform rules and product claims before publishing.

## AI Image Product Photo

Source: [prompts/05-image-and-video-generation.md](../prompts/05-image-and-video-generation.md#image-prompt-reverse)

### Use Case

Turn product or reference information into a clean AI image prompt.

### Best For

- AI image creators
- E-commerce visual teams
- Product mockup workflows

### Input Variables

- `{product_name}`
- `{product_features}`
- `{background_style}`
- `{camera_angle}`
- `{lighting}`
- `{aspect_ratio}`

### Prompt

```text
Create an AI image prompt for a product photo.

Product: {product_name}
Product features to preserve: {product_features}
Background style: {background_style}
Camera angle: {camera_angle}
Lighting: {lighting}
Aspect ratio: {aspect_ratio}

Output one complete image-generation prompt that includes:
- Subject and product details
- Composition
- Background
- Lighting
- Material and texture
- Camera style
- Negative constraints

Rules:
- Do not change the product shape, logo, color, or visible structure.
- Do not add fake awards, fake certifications, fake user numbers, or fake discounts.
- Keep the final prompt ready to copy.
```

### Example Input

```text
product_name: polarized sunglasses
product_features: black frame, blue reflective lens, visible logo
background_style: clean outdoor summer light
camera_angle: three-quarter close-up
lighting: soft natural sunlight
aspect_ratio: 4:5
```

### Expected Output

A single detailed image prompt plus negative constraints.

### Notes

Use only product facts that can be verified from the reference image or product sheet.

## Product Poster Prompt

Source: [prompts/09-banana-ecommerce-and-poster.md](../prompts/09-banana-ecommerce-and-poster.md#banana-commercial-poster-generator)

### Use Case

Generate a commercial poster prompt from a product image and campaign direction.

### Best For

- Product poster designers
- E-commerce operators
- AI image prompt writers

### Input Variables

- `{product_name}`
- `{campaign_goal}`
- `{visual_style}`
- `{main_headline}`
- `{supporting_copy}`
- `{brand_colors}`

### Prompt

```text
You are a senior commercial poster designer and AI image prompt builder.

Task: Create a poster-generation prompt for {product_name}.

Campaign goal: {campaign_goal}
Visual style: {visual_style}
Main headline: {main_headline}
Supporting copy: {supporting_copy}
Brand colors: {brand_colors}

Output:
1. Short product and audience analysis.
2. Layout recommendation.
3. Final poster prompt.
4. Negative prompt.

Rules:
- Keep the product accurate.
- Use clean typography and readable layout.
- Do not include fake sales numbers, fake awards, or fake platform claims.
```

### Example Input

```text
product_name: polarized sunglasses
campaign_goal: summer outdoor promotion
visual_style: clean magazine editorial
main_headline: Clear Vision Outdoors
supporting_copy: Lightweight comfort for sunny days
brand_colors: black, silver, pale blue
```

### Expected Output

A ready-to-copy poster prompt with layout, typography, and negative constraints.

### Notes

If the image model struggles with exact text, generate the background first and add text in a design tool.

## Translation and Localization

Source: [prompts/02-translation-and-polishing.md](../prompts/02-translation-and-polishing.md#zh-to-th-localization)

### Use Case

Localize Chinese source copy into natural Thai or bilingual content.

### Best For

- Cross-border e-commerce teams
- TikTok content teams
- Localization reviewers

### Input Variables

- `{source_text}`
- `{target_language}`
- `{target_audience}`
- `{platform}`
- `{tone}`
- `{forbidden_terms}`

### Prompt

```text
You are a localization editor familiar with {target_language} and {platform}.

Task: Localize the following source text into natural {target_language}.

Source text:
{source_text}

Audience: {target_audience}
Platform: {platform}
Tone: {tone}
Forbidden terms: {forbidden_terms}

Output:
1. Localized version.
2. Literal meaning notes when useful.
3. Cultural or platform-risk notes.
4. Alternative version with a different tone.

Rules:
- Do not translate word by word if it sounds unnatural.
- Keep product claims factual.
- Flag uncertain slang, claims, or cultural risks.
```

### Example Input

```text
source_text: 这副偏光墨镜适合开车、钓鱼和户外运动。
target_language: Thai
target_audience: adults interested in outdoor activities
platform: TikTok Shop
tone: friendly and practical
forbidden_terms: absolute claims, fake discounts
```

### Expected Output

A localized version plus notes explaining cultural and platform considerations.

### Notes

Have a native speaker review final customer-facing Thai copy when possible.

## AI Video Storyboard

Source: [prompts/05-image-and-video-generation.md](../prompts/05-image-and-video-generation.md#product-ad-4x4-storyboard)

### Use Case

Plan a product video storyboard for AI video or image-grid generation.

### Best For

- AI video users
- Product advertisers
- Storyboard creators

### Input Variables

- `{product_name}`
- `{story_goal}`
- `{scene}`
- `{visual_style}`
- `{shot_count}`
- `{aspect_ratio}`

### Prompt

```text
Create a product video storyboard for {product_name}.

Story goal: {story_goal}
Scene: {scene}
Visual style: {visual_style}
Shot count: {shot_count}
Aspect ratio: {aspect_ratio}

Output a storyboard table with:
- Shot number
- Visual description
- Camera angle / motion
- Product placement
- Action
- Caption or voiceover
- Notes for AI image/video generation

Rules:
- Keep product appearance consistent.
- Use different shot sizes and angles.
- Avoid cluttered scenes and fake claims.
```

### Example Input

```text
product_name: polarized sunglasses
story_goal: show outdoor comfort and style
scene: sunny coastal road and beach
visual_style: clean commercial lifestyle
shot_count: 8
aspect_ratio: 9:16
```

### Expected Output

A concise storyboard table ready for AI video production.

### Notes

Use fewer shots for fast TikTok ads and more shots for cinematic product stories.

## Workflow Automation Prompt

Source: [prompt-packs/us-market-automation.md](../prompt-packs/us-market-automation.md)

### Use Case

Create a repeatable research or report-generation workflow with verification steps.

### Best For

- Operators building daily reports
- Research assistants
- Automation workflow builders

### Input Variables

- `{report_topic}`
- `{data_sources}`
- `{report_date}`
- `{target_audience}`
- `{output_format}`

### Prompt

```text
You are a careful research assistant.

Task: Generate a structured report about {report_topic}.

Report date: {report_date}
Audience: {target_audience}
Required sources: {data_sources}
Output format: {output_format}

Workflow:
1. Collect the latest available information from reliable sources.
2. Separate verified facts from interpretation.
3. Cite source names and dates.
4. Highlight uncertainty or missing data.
5. Produce the final report in {output_format}.

Rules:
- Do not invent numbers, events, or source names.
- Mark outdated or unverified information.
- Keep the report concise and decision-oriented.
```

### Example Input

```text
report_topic: daily US market summary
data_sources: official exchange data, major financial news, company filings
report_date: YYYY-MM-DD
target_audience: Chinese-speaking retail investors
output_format: Markdown report
```

### Expected Output

A sourced, date-aware report with facts, interpretation, and uncertainty clearly separated.

### Notes

For financial information, always check current data before publishing.
