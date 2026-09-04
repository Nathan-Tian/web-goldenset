# Golden Set 第 10 组：兰州牛肉面的故事

## Prompt

Create a complete single-page cultural storytelling website titled:

**“The Story of Lanzhou Beef Noodles”**

The website should introduce Lanzhou beef noodles to a global audience, not as a restaurant or food ordering website, but as a story about Chinese food culture, craftsmanship, people, and everyday life.

Include:

- The origin and cultural background of Lanzhou beef noodles
- The traditional noodle-making process
- The role of broth, hand-pulled noodles, beef, and local ingredients
- The people and craftsmanship behind the dish
- How Lanzhou beef noodles became part of everyday life
- Its cultural influence beyond Lanzhou
- A meaningful closing section about food, memory, and cultural connection

The content should be easy to understand for international visitors who may know little about Lanzhou or Chinese food culture.

Please freely decide the visual style, layout, typography, imagery, interactions, and storytelling approach.

Do not make it feel like a restaurant website, recipe page, or simple food encyclopedia.

Build it as a polished, responsive, standalone single-page frontend website with no login, backend, database, or external API requirements.

---

## Golden Set 标注

- **Good：** https://nathan-tian.github.io/web-goldenset/pair-10/good/
- **Bad：** https://nathan-tian.github.io/web-goldenset/pair-10/bad/

两版都覆盖了提示词要求的主要内容，也都能以单文件独立运行。优先交付 Good：米白与深绿的章节变化、清楚的图文层级，以及从城市、手艺到日常生活和记忆的推进，更适合国际读者阅读；资料来源与 AI 图像说明也更明确。

## Bad Reason

- 首屏金色大标题、发光面碗、桥影与说明文字叠在一起，局部文字压在插画上，视觉焦点相互争抢，主次不如 Good 清楚。
- 深色背景上大量使用偏暗的小字，工艺和日常生活章节又连续采用密集卡片，阅读负担较重；人物与生活场景主要依靠文字和简化图形表达，生活气息不如 Good 直观。
- 响应式细节不够精致：390px 手机视口下“四绿”被拆到两行；面型详情弹窗在桌面和手机尺寸下都出现了横向滚动条。
- 页面自称“documentary”，却把未注明来源的文字写成地方俗语和师傅直接引语，部分表述过于绝对；“八九次拉伸得到 256–1,024 根”的说明，也与自身模拟器中九次得到 512 根不一致，降低了文化介绍的可信度。
- 结尾加入“Try it at home”的食材采购和烹煮建议，略微偏离用户明确要求的非食谱式文化叙事。

Bad 的原创 SVG、面型介绍和拉面模拟器有实际价值，并非没有完成任务。这里的 Good/Bad 是相对交付质量的判断；Good 也并非没有不足，其单文件约 18.18 MB，明显大于 Bad 的约 7.06 MB，资源体积仍有优化空间。
