# cnYui README 精简执行计划

## 目标

将 `cnYui` 更新为简洁的 GitHub 个人介绍仓库。

## 文件变更

- 修改：`README.md`
- 删除：`SETUP.md`
- 删除：`SNAKE_SETUP.md`
- 删除：`.github/workflows/snake.yml`
- 新增：`docs/ai/context/20260527-172005-readme-simplify-design.md`
- 新增：`docs/ai/context/20260527-172005-readme-simplify-plan.md`

## 步骤

- [x] 用 `yui.web` 的个人资料信息重写 `README.md`。
- [x] 删除贪吃蛇动画和设置说明相关文件。
- [x] 检查仓库文件列表，确认不再引用贪吃蛇。
- [x] 查看 `git diff`，确认没有误删无关内容。

## 验证

- 运行 `rg -n "snake|贪吃蛇|readme-typing-svg|github-readme-stats|trophy|Spotify|jokes" .`。
- 运行 `git diff --stat`。
- 人工检查 `README.md` 内容是否简洁、中文为主、联系方式正确。
