# 学习网站与学习方法 Skills

按用途整理的公开 Agent Skills 清单。链接指向原项目；使用前请阅读对应的 `SKILL.md`、许可证和依赖说明。

**[查看目前安装的 999 个 Skills](ALL_INSTALLED_SKILLS.md)**。另列出 43 个插件缓存条目；下方保留与学习网站最相关的 7 个。

## 网站开发

| 分类 | Skill | 用途 | 来源 |
| --- | --- | --- | --- |
| 界面设计 | frontend-design | 设计课程页、学习面板等前端界面 | [Anthropic](https://github.com/anthropics/skills/tree/main/skills/frontend-design) |
| 体验检查 | web-design-guidelines | 检查交互、布局和无障碍问题 | [Vercel](https://github.com/vercel-labs/agent-skills/tree/main/skills/web-design-guidelines) |
| React 开发 | react-best-practices | 优化 React／Next.js 网站的性能与代码 | [Vercel](https://github.com/vercel-labs/agent-skills/tree/main/skills/react-best-practices) |
| 功能测试 | webapp-testing | 用浏览器验证网站功能与界面行为 | [Anthropic](https://github.com/anthropics/skills/blob/main/skills/webapp-testing/SKILL.md) |

## 学习方法与内容

| 分类 | Skill | 用途 | 来源 |
| --- | --- | --- | --- |
| 课程制作 | anything-to-course | 把现有资料转成自学课程、练习和复习计划 | [lowwwbank](https://github.com/lowwwbank/anything-to-course) |
| 互动辅导 | study-skill | 对话教学、练习与间隔复习 | [mordor-forge](https://github.com/mordor-forge/study-skill) |
| 学习资料 | the-learning-skill | 生成笔记、闪卡、测验与复习日程 | [toddward](https://github.com/toddward/the-learning-skill) |

## 用在当前学习站

当前站点在 `sites/htawbi-learning/`，是无需构建的静态网站。优先使用 `frontend-design` 和 `webapp-testing`；`react-best-practices` 仅在站点采用 React／Next.js 时使用。制作新学科的学习内容时，可参考 `anything-to-course`、`study-skill` 和 `the-learning-skill`。
