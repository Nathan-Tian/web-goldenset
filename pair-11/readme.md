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

- **Good：** https://nathan-tian.github.io/web-goldenset/pair-11/good/
- **Bad：** https://nathan-tian.github.io/web-goldenset/pair-11/bad/

## Bad Reason

- 页面未完成：无任何样式，浏览器默认字体与左上角堆叠布局，其余为大面积空白。
- 日期与地点仍是 `--` 占位符，未提供参加活动所需的基本信息。
- 缺失活动介绍、艺人阵容、演出日程、活动体验、票价与访客须知等全部主要内容。
- 图片使用无效的内嵌数据，渲染为破损图片与替代文字，无法承担主题展示作用。
- `Get tickets` 按钮绑定空回调，点击无任何反馈，唯一的主要操作不可用。
- `Loading...` 始终停留在页面上，没有后续加载流程，页面持续呈现未完成状态。
