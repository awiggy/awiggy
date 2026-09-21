# 个人作品集封面海报

- 用途：GitHub 个人主页 README 顶部的可点击封面，链接至 https://awiggy.github.io/ 。
- 文件：`portfolio-cover.png`，1920 × 1080，16:9，PNG。
- 风格参考：个人网站现有首屏；奶油白、深棕、橙色手写与皮革笔记本。
- 生成方式：内置 imagegen（built-in），未使用 CLI/API fallback。生成后仅做标准尺寸与 PNG 导出，未改写图内内容。
- 原自我介绍和其余 README 内容保持不变。跳转由 README 图片外层链接实现，不由图片实现。

## 最终生成提示词

```text
Use case: ads-marketing.
Asset type: GitHub profile portfolio cover poster, landscape EXACT 16:9 aspect ratio, 1920x1080 or 1536x864 pixels.
Input Image 1 is the owner's existing personal portfolio website, a visual identity reference, NOT a UI screenshot to reproduce. Create a polished standalone invitation poster which looks like the same website, with no browser chrome.
Style: warm minimalist editorial scrapbook, generous ivory paper background #fdfbf9, dark cocoa ink #2b1a07, vivid orange handwritten accents #ff6f1e, tactile photorealistic cognac leather notebook and yellow pencil. Same chunky soft lowercase headline typography as the reference (Lilita One-like), Chinese supporting copy in refined readable dark serif. Clean composition, not crowded, not technical/cyberpunk.
Layout: left 52% is type, starting 7% inset. Top left a small orange handwritten line "Dear curious minds,". Below a very large dark headline on two lines exactly "meet" and "awiggy". Below the headline two short Chinese lines exactly "把具体的问题，" and "做成可以体验的作品。" with a small orange handwritten "make it real!" beside them. Near lower-left a thin dark outlined cream pill with text exactly "翻开我的作品集 ↗". Bottom-left small legible text "AI 产品 · Projects & Skills".
Right 46%: a beautiful large cognac leather notebook matching the reference with fine leather grain and stitching, tilted slightly counterclockwise, extending beyond the bottom-right edge elegantly but KEEP its white school name label fully visible. The white label has a thin double dark border and clear black handwritten "awiggy", smaller "AI product" below. A yellow pencil is in its right loop. Soft realistic shadow on the warm paper.
Use a single tiny playful hand-drawn orange curved arrow near the CTA or notebook; no other unnecessary decorative objects. All critical text sits within a 6% safe margin and remains readable at 800px display width. Render text accurately. No additional slogans, no other brands, no watermark, no QR code. The whole canvas has an opaque warm ivory background. This is the top cover for clicking into https://awiggy.github.io/ but DO NOT print URL, interaction is implemented separately in GitHub README.
```
