# Golden Set 第 11 组：夏日海滩音乐节

## Prompt

Create a complete single-page website for a fictional event called:

**“Summer Beach Music Festival”**

The website should promote a large summer music festival held by the sea.

Include:

- Event introduction
- Date and location
- Artist lineup
- Festival schedule
- Activities and experiences
- Ticket information
- Practical visitor information
- A final call to action

The page should feel like a complete event website rather than a simple event poster or information page.

Please freely decide the visual style, layout, typography, imagery, interactions, and presentation.

Build it as a polished, responsive, standalone single-page frontend website with no login, backend, database, or external API requirements.

---

## Golden Set 标注

- **Good：** [Summer Beach Music Festival](https://nathan-tian.github.io/web-goldenset/pair-11/good/)
- **Bad：** [Summer Beach Music Festival](https://nathan-tian.github.io/web-goldenset/pair-11/bad/)

本组用于校准评分刻度的两端：Good 是完整的高分参照，Bad 是按要求刻意制作的近乎空白、明显未完成的低分对照，不是两份完成度接近的方案之间的风格比较。

Good 覆盖活动介绍、日期地点、18 组艺人、三天演出安排、海滩体验、三档门票、访客须知和结尾引导。海岸大图、艺人照片、清楚的文字层级和不同章节布局组成了完整的活动网站；艺人筛选、日程切换、收藏演出、日历下载和选票演示也都有对应行为。购票流程明确说明只是演示，不会实际预订或扣款。

两版均为单个 `index.html`，CSS 和 JavaScript 已内嵌；Good 的图片与字体也已内嵌，不需要额外资源文件、后端或外部 API。Bad 的图片损坏是页面自身的固定缺陷，不依赖网络请求失败来制造差异。

## Bad Reason

- 页面只有左上角少量文字、一个破损图片和一个按钮，其余区域大面积空白；没有海滩音乐节应有的图文展示、章节组织或完整活动体验。
- 日期和地点仍是 `--` 占位符，连参加活动所需的基本信息也没有提供。
- 缺失活动介绍、艺人阵容、演出日程、活动体验、票价和访客须知等主要内容，无法完成原提示词要求的核心任务。
- 图片使用无效的内嵌数据，显示破损图片或替代文字，不能承担主题展示作用。
- `Get tickets` 按钮绑定空回调，点击后没有跳转、选票界面或任何反馈，唯一的主要操作也不可用。
- `Loading...` 始终停留在页面上，没有加载流程或后续内容，使页面持续呈现未完成状态。

低分依据是实际缺失的内容、破损展示和无效操作，而不是白色背景、代码短或没有后端。页面内部没有提示评估器给高分或低分的文字。Good 也不等于毫无不足：单文件约 14.92 MB，资源体积仍有优化空间；本组不预设具体分数，用于检查完整交付与明显失败是否被放在评分刻度的正确两端。
