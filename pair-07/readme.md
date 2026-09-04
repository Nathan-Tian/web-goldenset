# Golden Set 第 7 组：敦煌壁画数字艺术展

## Prompt

Create a complete single-page exhibition website for a global audience titled:

**“Dunhuang Murals: A Digital Art Exhibition”**

The website should introduce the cultural and artistic significance of the Dunhuang murals and present them as a digital exhibition experience.

Include:

- An introduction to Dunhuang and the Mogao Caves
- Several representative murals or artworks
- Different exhibition chapters or themes
- Historical and cultural context
- Visitor or exhibition information
- A meaningful closing section about preserving and sharing cultural heritage

The content should be accessible and engaging for international visitors who may not be familiar with Chinese history or Dunhuang culture.

Please freely decide the visual style, layout, typography, imagery, interactions, and presentation.

Do not make it feel like a simple encyclopedia or information page.

Build it as a polished, responsive, standalone single-page frontend website with no login, backend, database, or external API requirements.

---

## Golden Set 标注

- **Good：** [查看页面](https://nathan-tian.github.io/web-goldenset/pair-07/good/)
- **Bad：** [查看页面](https://nathan-tian.github.io/web-goldenset/pair-07/bad/)

**交付建议：选择 Good。** 真实壁画的图像、青绿色与浅色背景的搭配、清晰的留白，更能突出敦煌艺术本身；章节筛选、画作缩放和细节导读也更贴近观展需求。Bad 的暗色氛围统一，五个展区及颜料介绍覆盖更广，但综合视觉表现、阅读体验和交付可信度，Good 更符合这份提示词。

## Bad Reason

- 展品主要用简单的 SVG 人物和几何图形再创作，难以呈现原壁画细密的线条、色彩层次与斑驳肌理。虽然页脚和弹窗注明了再创作身份，但作为敦煌壁画展，观众仍缺少直接欣赏原作图像的机会。
- 大面积深褐背景、重复的图文框架和连续长段介绍，使各展区的阅读节奏较单一。内容虽丰富，却更依赖读文字了解艺术，弱化了“先看作品、再按兴趣深入”的数字展览体验。
- 手机端的顶部品牌文字过长，挤压了菜单空间；在 390px 宽视口下，文档宽度达到 416px，右侧导航出现溢出，响应式收尾不够完整。
- 页面显示“128,634 位访客已承诺保护壁画”，实际是写死的初始数字，点击后仅在当前页面加一，且未注明是演示数据。把这种数字当作真实参与统计呈现，会影响面向用户交付时的可信度。
