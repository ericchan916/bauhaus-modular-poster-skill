---
name: bauhaus-modular-poster-skill
description: Generate a Simplified-Chinese 9:16 poster in the 「包豪斯几何」(bauhaus-modular) style by 一张有戏. Use when the user wants a 包豪斯几何 / bauhaus modular poster.
---

# 包豪斯几何 · bauhaus-modular poster skill

一张有戏「包豪斯几何」风格海报技能。输出一张 9:16 竖版、简体中文的独立海报。

## 用法
1. 确定一个主标题（2–4 字）和一句短句。
2. 画面只出现三段文字：主标题、短句、页脚「一张有戏 · 视觉习作」。
3. 版式可选：big-type-only, modular-grid。
4. 参照下方完整提示词模板，替换 Headline / Supporting phrase / 场景描述。

## 示例主题
- 圆的旅行：沿着几何找到新的方向（modular-grid）— Three unequal circles and one blue tangent, disciplined red/yellow/black modules on cream, no random ornament.
- 模块练习：把秩序放进大小之间（big-type-only）— Unequal square modules, one red square and a blue semicircle, measured black gutters and strong title hierarchy.
- 节拍：让形状有自己的速度（modular-grid）— Repeated black circle-square pairs with one red interruption, rational clean proportional spacing, cream ground.
- 平衡：轻与重共同决定位置（big-type-only）— A geometric black lever, red circle and blue square in precise optical balance, one subtle yellow module.
- 相遇：不同形状共享一段关系（modular-grid）— One blue circle tangential to red triangle in an asymmetrical grid, large open cream area and functional Chinese type.
- 旋转：在同一中心看见变化（big-type-only）— Half circles and offset black arcs rotate around a clear modular center, measured red/yellow accents, not kaleidoscope clutter.
- 构成：让比例成为画面的语言（modular-grid）— Black rectangle, red circle and blue thin lines occupy unequal aligned modules; crisp restrained primary color geometry.
- 起点：从一个小圆开始展开（big-type-only）— One small red circle releases a proportional sequence of black and blue line modules, huge functional title, clean cream background.

## 完整提示词模板（第 1 张原文）
```
Use case: ads-marketing. Create exactly ONE polished professional 9:16 portrait poster, static flat artwork, Chinese-mainland cultural/creative studio portfolio concept.
Language: Simplified Chinese. Headline: 圆的旅行. Supporting phrase: 沿着几何找到新的方向. Tiny plain footer: 一张有戏 · 视觉习作. Exact visible text ONLY these three phrases, every character correctly formed. No English, random numbers, fake events, dates, addresses, awards, offers, prices, affiliations, calls to action or status labels. All content is fictional/conceptual creative brief, no real client claim.

SOURCE UNIVERSAL RULES:


These rules apply to every poster. Do not repeat them in layout or style notes.

- Build around one dominant message, one clear focal point, and one communication goal.
- Establish a simple reading order: headline -> focal image -> supporting copy -> supplied details.
- Preserve required copy exactly unless the user explicitly asks for rewriting.
- Keep important text readable, high-contrast, and inside safe margins.
- Use confident spacing and avoid overstuffed layouts.
- Avoid fake extra text, random logos, QR codes, decorative clutter, malformed typography, and generic AI-poster noise.
- Treat the poster canvas as static print/editorial artwork rather than a clickable interface. If the source explicitly requests a product UI, browser window, dashboard, or device mockup, preserve that depicted content inside the poster.
- CTA copy is extractive-only: include it only when the source explicitly supplies the wording. When output language differs, verify the translated CTA against a recorded exact source quote. Never invent action or status labels.
- If no CTA is sourced, leave the action area empty. If one is sourced, render it as ordinary poster typography in a footer or text lockup. Do not place poster-level action copy inside a button, rounded rectangle, pill, chip, capsule, tab, input field, or any other clickable-looking UI container; do not decorate it with a shadow, arrow, chevron, or cursor icon.



SELECTED STYLE — STRICTLY THIS VISUAL SYSTEM, DO NOT MIX OTHER STYLES:
# Bauhaus Modular

## Intent

Create a rational, geometric poster with modular clarity, functional typography, and disciplined primary-color accents.

## Typography

- Use geometric sans-serif direction.
- Favor clean hierarchy, numbers, labels, and modular text placement.
- Keep type functional and balanced with shapes.

## Palette

White/cream/black base with red, blue, yellow, and occasional gray. Use accents sparingly and structurally.

## Imagery

Use circles, squares, lines, grids, simple diagrams, abstract forms, or minimal product/object photography.

## Texture / Material

Clean flat color, slight paper grain, print registration feel, simple vector-like surfaces.

## Composition Rules

- Build with clear modules and geometric relationships.
- Use repetition, alignment, and proportional spacing.
- Make ornament functional.
- Let shapes carry rhythm and direction.

## Avoid

Childlike geometric clutter, too many primary colors, decorative randomness, soft gradients, and weak hierarchy.


INTERNAL COMPOSITION:
# Modular Grid

## Composition Structure

- Use a visible or invisible grid of cards, cells, or modules.
- Assign different scale to key modules for hierarchy.
- Use repeated spacing and consistent alignment.
- Reserve one module for the headline or master label.

## Hierarchy Rules

1. Largest module carries headline or key visual.
2. Medium modules carry sections or benefits.
3. Small modules carry details or metadata.

## Text Placement

- Keep text inside modules with consistent padding.
- Use short labels, numbers, and compact paragraphs.
- Treat details as a system, not scattered annotations.

## Image Treatment

Use icons, cropped photos, small diagrams, abstract shapes, or texture blocks inside cells.

## Spacing Rules

Grid gutters must be consistent. Use whitespace as structure.

## Aspect-Ratio Behavior

Works across all ratios; use fewer columns in narrow ratios and more columns in `16:9`.

## Avoid

Equal module importance, over-dense cells, inconsistent gutters, and decorative grids with no content logic.


SPECIFIC SUBJECT AND ART DIRECTION:
Three unequal circles and one blue tangent, disciplined red/yellow/black modules on cream, no random ornament.

Quality: exquisite thoughtful art direction, one immediate focal point, sophisticated typographic spacing and clear reading order, original expressive composition with wide enough safe margins. Headline large and readable at phone thumbnail; secondary text restrained, not generic template. Typography adapted sensitively to real Chinese glyphs, with the visual weight demanded by style. Material/light/print treatment consistent with selected style. If any person appears, fictional mainland Chinese adult, natural anatomy and authentic face; otherwise no people. All props physically coherent unless the SPECIFIC surreal idea deliberately changes physics. No trademarks or label text on products, no fake logos/watermarks/QR. No poster mockup, wall frame, multiple-poster collage, UI buttons or decorative website components. The creative theme must determine composition; vary crop, hierarchy and negative space across the series. Output one finished poster only.
```

全部 8 条提示词见 `PROMPTS.json`，来源见 `SOURCES.md`。
