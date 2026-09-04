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

- 页面只有左上角少量文字、一个破损图片和一个按钮，其余区域大面积空白；没有海滩音乐节应有的图文展示、章节组织或完整活动体验。
- 日期和地点仍是 `--` 占位符，连参加活动所需的基本信息也没有提供。
- 缺失活动介绍、艺人阵容、演出日程、活动体验、票价和访客须知等主要内容，无法完成原提示词要求的核心任务。
- 图片使用无效的内嵌数据，显示破损图片或替代文字，不能承担主题展示作用。
- `Get tickets` 按钮绑定空回调，点击后没有跳转、选票界面或任何反馈，唯一的主要操作也不可用。
- `Loading...` 始终停留在页面上，没有加载流程或后续内容，使页面持续呈现未完成状态。
