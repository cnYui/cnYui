# cnYui README 精简设计

## 目标

把 `cnYui` 仓库的 GitHub 个人主页从装饰型模板改成简洁的个人介绍。

## 参考来源

- `D:\CodeWorkSpace\yui.web\SKILL.md`
- `D:\CodeWorkSpace\yui.web\index.html`
- `D:\CodeWorkSpace\yui.web\resume\index.html`

## 设计决策

- 只保留 `README.md` 作为主页主体。
- 删除统计卡片、贪吃蛇、小游戏、玩笑、技能进度条、ASCII、无效社交链接等噪声。
- 使用中文为主，保留少量必要英文身份关键词，例如 `AI Native Developer`。
- 内容聚焦：身份、关注方向、技术与创作方式、联系方式。
- 删除 `SETUP.md`、`SNAKE_SETUP.md` 和 `.github/workflows/snake.yml`，因为它们只服务于已移除的贪吃蛇动画。

## README 结构

1. 标题：`Yui / 悠一`
2. 一段简介：研究生、AI Native Developer、独立开发者、设计师、创作者
3. 关注方向：AI 工作流、Agent、RAG、GraphRAG、产品体验
4. 技术与工具：Python、React、TypeScript、LangChain、LangGraph 等
5. 经历关键词：福井大学、黑客松、AI Native 产品
6. 联系方式：邮箱、个人网站

## 取舍

不再保留动态徽章和外部生成图片。它们视觉上热闹，但会稀释个人介绍，也依赖第三方服务，和“最简洁”的目标冲突。
