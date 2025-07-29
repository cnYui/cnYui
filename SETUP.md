# GitHub Profile 贪吃蛇动画设置指南

## 📋 设置步骤

### 1. 创建GitHub仓库
1. 在GitHub上创建一个新仓库
2. 仓库名必须与你的GitHub用户名完全相同（例如：`cnYui`）
3. 设置为公开仓库（Public）
4. 勾选"Add a README file"

### 2. 上传文件
1. 将本地的所有文件上传到GitHub仓库
2. 确保包含以下文件：
   - `README.md` - 主要的个人资料页面
   - `.github/workflows/snake.yml` - GitHub Actions工作流文件

### 3. 启用GitHub Actions
1. 进入你的仓库页面
2. 点击"Actions"标签页
3. 如果看到提示，点击"I understand my workflows, go ahead and enable them"
4. 找到"Generate Snake"工作流
5. 点击"Run workflow"手动运行一次

### 4. 个性化设置

#### 修改个人信息
在`README.md`文件中更新以下内容：
- 个人介绍和技能
- 联系方式链接
- 社交媒体链接
- 技术栈徽章

#### 自定义贪吃蛇动画
在`.github/workflows/snake.yml`文件中，你可以修改：
- `github_user_name`: 确保设置为你的GitHub用户名
- 运行频率：修改`cron`表达式（当前为每6小时运行一次）
- 输出格式：可以添加不同的颜色主题

## 🎨 自定义选项

### 贪吃蛇颜色主题
你可以在工作流文件中添加自定义颜色：

```yaml
outputs: |
  dist/github-contribution-grid-snake.svg
  dist/github-contribution-grid-snake-dark.svg?palette=github-dark
  dist/ocean.gif?color_snake=orange&color_dots=#bfd6f6,#8dbdff,#64a1f4,#4b91f1,#3c7dd9
```

### 可用的调色板
- `github` - GitHub默认主题
- `github-dark` - GitHub深色主题
- `github-light` - GitHub浅色主题

### 自定义颜色
- `color_snake` - 贪吃蛇的颜色
- `color_dots` - 贡献点的颜色（5个颜色，从低到高贡献度）

## 🔧 故障排除

### 贪吃蛇动画不显示
1. 检查GitHub Actions是否成功运行
2. 确保仓库名与用户名完全匹配
3. 确保仓库是公开的
4. 等待几分钟让GitHub Pages更新

### GitHub Actions失败
1. 检查工作流文件语法是否正确
2. 确保GitHub Actions已启用
3. 查看Actions日志获取详细错误信息

## 📚 更多资源

- [GitHub Profile README官方文档](https://docs.github.com/en/account-and-profile/setting-up-and-managing-your-github-profile/customizing-your-profile/managing-your-profile-readme)
- [Platane/snk项目](https://github.com/Platane/snk) - 贪吃蛇动画生成器
- [GitHub Actions文档](https://docs.github.com/en/actions)

## 🎉 完成！

设置完成后，你的GitHub个人资料页面将显示：
- 美观的个人介绍
- 技术栈徽章
- GitHub统计信息
- 动态的贪吃蛇动画
- 支持深色/浅色模式

动画会每6小时自动更新一次，展示你最新的贡献图表！