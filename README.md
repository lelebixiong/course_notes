# 📚 GitHub 与 Git 课程笔记

![GitHub Banner](https://github.githubassets.com/images/modules/site/social-cards/github-social.png)

[![GitHub license](https://img.shields.io/github/license/yourusername/your-repo?style=flat-square)](https://github.com/yourusername/your-repo/blob/main/LICENSE)
[![GitHub stars](https://img.shields.io/github/stars/yourusername/your-repo?style=flat-square)](https://github.com/yourusername/your-repo/stargazers)
[![GitHub issues](https://img.shields.io/github/issues/yourusername/your-repo?style=flat-square)](https://github.com/yourusername/your-repo/issues)

本仓库包含系统整理的 GitHub 和 Git 学习笔记，涵盖从基础到进阶的所有核心概念，适合开发者、学生和任何希望掌握版本控制的用户。

## 🚀 快速导航

- [课程内容](#-课程内容)
- [项目结构](#-项目结构)
- [如何使用](#-如何使用)
- [示例代码](#-示例代码)
- [学习路线](#-学习路线)
- [常见问题](#-常见问题)
- [贡献指南](#-贡献指南)
- [许可证](#-许可证)

## 📖 课程内容

### 基础篇
- Git 基本概念（仓库、提交、分支）
- 常用命令（`init`, `add`, `commit`, `push`, `pull`）
- .gitignore 文件配置
- GitHub 仓库创建与管理

### 进阶篇
- 分支策略（Git Flow, GitHub Flow）
- 解决合并冲突
- 交互式 rebase
- 标签管理与版本发布

### 协作篇
- Fork & Pull Request 工作流
- Code Review 最佳实践
- GitHub Issues 和 Projects 使用
- 团队权限管理

### 工具篇
- GitHub CLI 使用
- GitHub Actions 自动化
- GitHub Pages 部署
- IDE 集成（VS Code, IntelliJ）

## 📂 项目结构
.github/ - GitHub 工作流和 issue 模板
├── workflows/
│ └── ci.yml - CI 自动化脚本
docs/ - 详细文档和教程
examples/ - 示例项目
├── basic-git/ - 基础 Git 示例
├── github-actions/ - GitHub Actions 示例
notes/ - 分类笔记
├── 01-git-basics.md
├── 02-github-features.md
├── 03-collaboration.md
resources/ - 学习资源
├── cheatsheets/ - 速查表
├── videos/ - 推荐视频

复制

## 🛠 如何使用

### 本地使用
1. 克隆仓库：
   ```bash
   git clone https://github.com/yourusername/git-notes.git
安装依赖工具：

bash
复制
brew install git gh  # macOS
# 或
sudo apt-get install git gh  # Linux
浏览笔记目录：

bash
复制
cd git-notes/notes
ls
在线使用
直接浏览 GitHub 上的笔记文件，所有 Markdown 文件都支持 GitHub 渲染。

💻 示例代码
创建新分支并推送
bash
复制
# 创建并切换到新分支
git checkout -b feature/new-feature

# 进行更改后...
git add .
git commit -m "添加新功能"

# 推送到远程
git push -u origin feature/new-feature
撤销最后一次提交
bash
复制
git reset --soft HEAD~1
📈 学习路线
mermaid
复制
graph LR
    A[Git 基础] --> B[本地仓库操作]
    B --> C[远程仓库同步]
    C --> D[分支管理]
    D --> E[团队协作]
    E --> F[高级工具]
❓ 常见问题
<details> <summary>如何解决合并冲突？</summary>
运行 git status 查看冲突文件

打开冲突文件，查找 <<<<<<<, =======, >>>>>>> 标记

手动解决冲突后保存文件

使用 git add <file> 标记为已解决

完成合并提交

</details><details> <summary>如何撤销已推送的提交？</summary>
使用 git revert <commit-hash> 创建反向提交，这是最安全的远程仓库撤销方法。

</details>
🤝 贡献指南
欢迎贡献！请遵循以下步骤：

Fork 本仓库

创建特性分支 (git checkout -b feature/AmazingFeature)

提交更改 (git commit -m 'Add some AmazingFeature')

推送到分支 (git push origin feature/AmazingFeature)

打开 Pull Request

请确保：

代码风格一致

添加适当的文档

测试你的更改

📜 许可证
本项目采用 MIT 许可证 - 详情见 LICENSE 文件。

<div align="center"> <sub>由 <a href="https://github.com/yourusername">你的名字</a> 创建 | 最后更新于 2023-11-01</sub> </div> ```
功能特点
专业外观：包含徽章、结构化导航和美观排版

全面覆盖：从基础到高级的 Git/GitHub 知识点

交互元素：可折叠的常见问题解答部分

可视化内容：Mermaid 图表展示学习路线

实用代码示例：包含可直接运行的命令示例

贡献指南：清晰的协作说明

响应式设计：在 GitHub 和移动设备上都能良好显示
