# 迹忆（JiYi-Diary）

![Logo](docs/logo.png) <!-- 上传LOGO到仓库的docs目录 -->

**记录心灵的足迹，遇见更好的自己。**

[![GitHub License](https://img.shields.io/github/license/你的用户名/JiYi-Diary)](LICENSE)
[![Android CI](https://github.com/你的用户名/JiYi-Diary/actions/workflows/android.yml/badge.svg)](https://github.com/你的用户名/JiYi-Diary/actions) <!-- 后续配置CI后添加 -->

## ✨ 功能亮点
- **多维度日记模板**：学习、减肥、情绪自愈等场景化记录。
- **智能推荐系统**：根据情绪数据推荐书籍或行动建议。
- **数据可视化**：生成成长曲线与统计图表。

## 🛠️ 技术栈
- **语言**: Kotlin
- **架构**: MVVM + Clean Architecture
- **数据库**: Room + SQLite
- **网络**: Retrofit (未来集成卡路里API)
- **图表**: MPAndroidChart

## 🚀 快速开始
```bash
# 克隆项目
git clone https://github.com/你的用户名/JiYi-Diary.git
# 使用 Android Studio 打开项目

## 🤝 如何贡献
参考 CONTRIBUTING.md。

## 📄 开源协议
本项目采用 GPL-3.0。


---

#### **4. 制定贡献指南（CONTRIBUTING.md）**
在仓库根目录创建 `CONTRIBUTING.md`，规范协作流程：
```markdown
# 贡献指南

## 开发流程
1. **创建 Issue**：描述问题或功能建议。
2. **Fork 仓库**：基于 `main` 分支创建你的分支。
3. **提交代码**：
   - 分支命名：`feat/新功能名` 或 `fix/问题描述`。
   - 代码风格：遵循 [Kotlin官方编码规范](https://kotlinlang.org/docs/coding-conventions.html)。
4. **发起 Pull Request**：关联对应 Issue，并请求团队审核。

5. 规划项目结构与开发路线
目录结构示例：

JiYi-Diary/
├── app/               # 主模块
│   ├── src/main/
│   │   ├── java/      # Kotlin 代码
│   │   └── res/       # 资源文件
├── build.gradle      # 项目级配置
├── docs/             # 设计文档、原型图
└── CONTRIBUTING.md
里程碑（Milestones）：

进入仓库 → Issues → Milestones → 创建：

Milestone 1: 基础框架（主页+模板选择）。

Milestone 2: 核心功能（数据存储+动态表单）。

Milestone 3: 推荐系统与数据可视化。

