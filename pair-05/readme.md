# Golden Set 第 5 组：There Is No Planet B · Protect the Earth

## Prompt

Create a complete single-page website for a global environmental awareness campaign.

Theme: Protect the Earth.

The website should feel modern, cinematic, emotional, and globally relevant. Avoid making it look like a corporate report, dashboard, or generic information website.

Include:

- A powerful hero section with Earth or nature imagery
- Environmental challenges such as climate change, plastic pollution, deforestation, ocean damage, and biodiversity loss
- A section showing what we are losing
- A hopeful section showing that change is possible
- Simple actions people can take to help protect the planet
- A strong final call to action

Suggested headline:

**“There Is No Planet B”**

Suggested final message:

**“Protect What We Share.”**

Use large nature photography, bold typography, strong visual hierarchy, smooth scrolling, and subtle animations.

The emotional flow should be:

**Beauty → Crisis → Hope → Action**

Build it as a polished responsive single-page frontend website for a global audience. No login, backend, database, or external API requests.

---

## Golden Set 标注

- **Good：** https://nathan-tian.github.io/web-goldenset/pair-05/good/
- **Bad：** https://nathan-tian.github.io/web-goldenset/pair-05/bad/

## Bad Reason

- Bad 版本的内容覆盖较全，也有明显的电影海报风格，但首屏同时堆叠了 “LIVE FEED”、CO₂ 数值、物种数量、评分、承诺人数和成立年份等信息，整体更像数据监测面板或营销活动模板，与提示词要求避开的 corporate report / dashboard 方向发生冲突。
- 提示词明确要求 large nature photography；Bad 版本的地球、草原、海洋、森林、冰川和珊瑚礁主要由 CSS 与内联 SVG 绘制，画面偏符号化插画。Good 版本则以地球轨道、海龟与珊瑚、森林边界和植树恢复等大幅自然摄影建立更直接、更真实的情绪冲击。
- Bad 版本在 Beauty 之后加入序章监测器、五个危机模拟面板、前后对比卡、灭绝名单、时间线、统计区、行动卡和承诺区，信息量过大且重复使用“标题 + 指标 + 卡片”的表达方式，Beauty → Crisis → Hope → Action 的主线因此被拉长并打散。Good 版本通过全屏摄影、黑场转折和明显的明暗变化，让危机转向希望的节奏更清楚。
- Bad 首屏混用了超大衬线体、斜体、等宽数据标签、边框徽章和多组按钮，视觉焦点彼此竞争；Good 以无衬线巨型标题、留白和单一绿色强调色形成更强的层级，第一眼即可读到 “There Is No Planet B”。
- Bad 使用 “4.9 — 128,000+ pledges”“LIVE FEED”“GLOBAL CAMPAIGN · EST. 1970”等未经说明的拟真数据和社会证明，承诺人数也只是在浏览器中临时递增。这些内容容易让正式公益交付产生可信度风险，而 Good 没有伪装成实时数据或真实组织背书。
- Bad 的承诺选项使用可点击的 `label` 和装饰性 `span` 模拟复选框，没有原生表单控件，也没有完整的键盘交互语义；Good 使用真实 checkbox、选中数量反馈、按钮状态和本地保存，使行动区更容易理解，也更适合键盘与辅助技术用户。
- Bad 依赖 Google Fonts 在线样式表，离线打开或网络受限时字体表现不可控，也不符合单文件交付应尽量自包含的要求。Good 的 CSS、JavaScript 与图片数据全部封装在 `index.html` 中，不需要后端、数据库或外部请求。
- Bad 虽然设置了若干断点，但 Beauty 场景由 JavaScript 写入内联双栏布局，窄屏下缺少对应的单栏覆盖，内容可能仍被挤在半屏；Good 针对 980px 和 640px 明确重排导航、图文、行动列表与结尾区域，响应式交付更稳妥。
- Good 最终用 “Protect What We Share.” 收束叙事，并把用户带回可勾选、可保存、可分享的具体行动；它在视觉、情绪和交互三个层面都更接近一支可滚动体验的全球环保公益短片，因此更值得作为本组的交付版本。
