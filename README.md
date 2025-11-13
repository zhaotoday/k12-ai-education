# 中小学编程教育平台知识体系

[![GitHub stars](https://img.shields.io/github/stars/zhaotoday/k12-coding-education.svg?style=social&label=Star)](https://github.com/zhaotoday/k12-coding-education)
[![GitHub forks](https://img.shields.io/github/forks/zhaotoday/k12-coding-education.svg?style=social&label=Fork)](https://github.com/zhaotoday/k12-coding-education)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

> 一个全面的中小学编程教育平台知识体系整理项目，涵盖知识体系、教育资源、竞品分析、开源项目、技术方案和业务模块等内容。

## 📚 目录

- [项目简介](#项目简介)
- [知识体系](#知识体系)
- [教育资源](#教育资源)
- [竞品分析](#竞品分析)
- [开源项目](#开源项目)
- [技术栈](#技术栈)
- [业务模块](#业务模块)
- [教程资源](#教程资源)
- [学习路线](#学习路线)
- [贡献指南](#贡献指南)

## 项目简介

本项目旨在为中小学编程教育平台的开发者、教育工作者和学习者提供一个全面的知识体系和资源集合。内容涵盖从编程基础到平台实现的各个方面。

**适用人群：**
- 教育平台开发者
- 编程教育工作者
- 产品经理和设计师
- 教育创业者
- 编程学习者

## 知识体系

详见 [知识体系文档](./docs/knowledge-system.md)

### 编程语言体系

#### 图形化编程（6-10 岁）
- **Scratch**：MIT 开发的图形化编程语言
- **Blockly**：Google 开发的可视化编程框架
- **Code.org**：面向儿童的编程学习平台
- **Tynker**：游戏化编程学习

#### 代码编程（10+ 岁）
- **Python**：入门友好，应用广泛
- **JavaScript**：Web 开发必备
- **C++**：竞赛和算法学习
- **Java**：面向对象编程
- **Swift**：iOS 开发
- **Kotlin**：Android 开发

### 计算机科学基础

- 算法与数据结构
- 计算思维
- 逻辑思维
- 问题分解与抽象
- 模式识别
- 调试与测试

### 应用领域

- Web 开发
- 移动应用开发
- 游戏开发
- 人工智能入门
- 机器人编程
- 物联网（IoT）

## 教育资源

详见 [教育资源文档](./docs/resources.md)

### 在线学习平台

#### 国际平台
- **[Code.org](https://code.org/)**：免费的计算机科学课程
- **[Scratch](https://scratch.mit.edu/)**：MIT 图形化编程平台
- **[Khan Academy](https://www.khanacademy.org/computing)**：免费编程课程
- **[Codecademy](https://www.codecademy.com/)**：互动式编程学习
- **[Coursera](https://www.coursera.org/)**：大学级编程课程
- **[edX](https://www.edx.org/)**：顶尖大学的在线课程
- **[freeCodeCamp](https://www.freecodecamp.org/)**：免费编程学习和认证

#### 国内平台
- **[编程猫](https://www.codemao.cn/)**：少儿编程教育平台
- **[核桃编程](https://www.hetao101.com/)**：AI 驱动的编程教育
- **[腾讯扣叮](https://kada.163.com/)**：游戏化编程学习
- **[网易卡搭](https://kada.163.com/)**：Scratch 中文社区
- **[慕课网](https://www.imooc.com/)**：IT 技能学习平台
- **[中国大学 MOOC](https://www.icourse163.org/)**：优质大学课程

### 编程工具

#### 在线编辑器
- **[Replit](https://replit.com/)**：在线 IDE
- **[CodePen](https://codepen.io/)**：前端代码展示
- **[JSFiddle](https://jsfiddle.net/)**：Web 开发测试
- **[Glitch](https://glitch.com/)**：协作编程平台

#### 桌面工具
- **VS Code**：轻量级代码编辑器
- **PyCharm Edu**：Python 教育版 IDE
- **Thonny**：Python 初学者 IDE
- **Mu Editor**：为初学者设计的 Python 编辑器

### 教材与书籍

- 《Python 编程：从入门到实践》
- 《JavaScript 儿童编程》
- 《动手学深度学习》
- 《算法图解》
- 《编程之美》
- 《计算机科学导论》

## 竞品分析

详见 [竞品分析文档](./docs/competitors.md)

### 国际竞品

| 平台 | 特点 | 目标年龄 | 商业模式 |
|------|------|----------|----------|
| **Code.org** | 非营利，免费课程体系完善 | 4-18 岁 | 非营利 + 捐赠 |
| **Scratch** | MIT 开发，全球最大儿童编程社区 | 8-16 岁 | 免费开源 |
| **Tynker** | 游戏化学习，课程体系丰富 | 5-17 岁 | 订阅制 |
| **CodeCombat** | 游戏式学习编程 | 9+ 岁 | 免费 + 订阅 |
| **Codecademy** | 互动式学习，即时反馈 | 13+ 岁 | 免费 + 订阅 |
| **Khan Academy** | 免费，课程全面 | 全年龄 | 非营利 + 捐赠 |

### 国内竞品

| 平台 | 特点 | 融资情况 | 优势 |
|------|------|----------|------|
| **编程猫** | 自主研发图形化工具，内容丰富 | D 轮 | 品牌知名度高 |
| **核桃编程** | AI 教学，1 对 1 辅导 | C+ 轮 | AI 驱动个性化 |
| **小码王** | 线上线下结合 | C 轮 | OMO 模式 |
| **VIPCODE** | 在线 1 对 1，真人教学 | B+ 轮 | 真人互动教学 |
| **西瓜创客** | AI 双师模式 | B+ 轮 | AI 辅助教学 |
| **傲梦编程** | VIP 1 对 1 | A 轮 | 个性化定制 |

### 核心竞争力分析

- **课程体系**：完整的进阶路径
- **教学模式**：AI + 真人教师
- **技术平台**：自研 vs 开源
- **内容质量**：原创性和趣味性
- **用户体验**：交互设计和激励机制
- **商业模式**：订阅、课程包、增值服务

## 开源项目

详见 [开源项目文档](./docs/open-source.md)

### 编程平台

#### Scratch 生态
- **[Scratch](https://github.com/scratchfoundation/scratch-gui)** ⭐ 4.5k
  - MIT 官方图形化编程平台
  - 技术栈：React, Redux
  
- **[Scratch Blocks](https://github.com/scratchfoundation/scratch-blocks)** ⭐ 1.3k
  - 基于 Blockly 的 Scratch 积木库

#### Blockly 生态
- **[Blockly](https://github.com/google/blockly)** ⭐ 12k
  - Google 开源的可视化编程库
  - 技术栈：JavaScript

- **[Blockly Games](https://github.com/google/blockly-games)** ⭐ 1.2k
  - 游戏化编程学习

#### 在线编程环境
- **[CodeMirror](https://github.com/codemirror/codemirror5)** ⭐ 26k
  - 浏览器代码编辑器组件

- **[Monaco Editor](https://github.com/microsoft/monaco-editor)** ⭐ 38k
  - VS Code 的编辑器核心

- **[Judge0](https://github.com/judge0/judge0)** ⭐ 2k
  - 代码执行引擎

### 教育系统

- **[Moodle](https://github.com/moodle/moodle)** ⭐ 5k
  - 开源学习管理系统 (LMS)

- **[Open edX](https://github.com/openedx/edx-platform)** ⭐ 7k
  - 大规模在线教育平台

- **[Canvas LMS](https://github.com/instructure/canvas-lms)** ⭐ 5.3k
  - 现代化学习管理系统

### AI 编程助手

- **[GitHub Copilot](https://github.com/features/copilot)**
  - AI 代码补全助手

- **[Tabnine](https://github.com/codota/tabnine-vscode)** ⭐ 900
  - AI 代码补全工具

### 游戏化学习

- **[Phaser](https://github.com/photonstorm/phaser)** ⭐ 36k
  - HTML5 游戏框架

- **[Pygame](https://github.com/pygame/pygame)** ⭐ 6.5k
  - Python 游戏开发库

## 技术栈

详见 [技术栈文档](./docs/tech-stack.md)

### 前端技术

#### 框架选择
- **React**：组件化开发
  - Next.js：SSR 和 SSG
  - React Native：移动端开发
  
- **Vue**：渐进式框架
  - Nuxt.js：SSR 框架
  - Uni-app：跨端开发

#### UI 组件库
- **Ant Design**：企业级 UI 设计
- **Material-UI**：Material Design
- **Element Plus**：Vue 3 组件库
- **Tailwind CSS**：原子化 CSS

#### 可视化编程
- **Blockly**：Google 图形化编程库
- **Scratch Blocks**：Scratch 3.0 积木库
- **Monaco Editor**：代码编辑器
- **CodeMirror**：轻量级编辑器

### 后端技术

#### 语言框架
- **Node.js**
  - Express：轻量级框架
  - Nest.js：企业级框架
  - Koa：下一代框架

- **Python**
  - Django：全栈框架
  - FastAPI：现代化 API 框架
  - Flask：微框架

- **Java**
  - Spring Boot：微服务框架
  - Spring Cloud：分布式系统

#### 数据库
- **关系型**
  - MySQL：开源数据库
  - PostgreSQL：功能强大

- **非关系型**
  - MongoDB：文档数据库
  - Redis：缓存和会话

#### 代码执行
- **Judge0**：代码评测系统
- **Docker**：容器化隔离
- **Kubernetes**：容器编排

### DevOps

- **容器化**：Docker, Docker Compose
- **CI/CD**：GitHub Actions, GitLab CI
- **监控**：Prometheus, Grafana
- **日志**：ELK Stack

### AI / 机器学习

- **TensorFlow.js**：浏览器端 ML
- **OpenAI API**：AI 辅助编程
- **自然语言处理**：智能提示和纠错

## 业务模块

详见 [业务模块文档](./docs/business-modules.md)

### 核心功能模块

#### 1. 用户系统
- 注册 / 登录（支持第三方登录）
- 用户角色（学生、教师、家长、管理员）
- 个人中心
- 学习档案
- 成就系统

#### 2. 课程系统
- 课程分类（图形化、代码、竞赛等）
- 课程详情
- 课程章节
- 课程评价
- 学习进度跟踪
- 课程推荐

#### 3. 编程环境
- 在线代码编辑器
- 实时代码执行
- 调试工具
- 代码保存和分享
- 多语言支持
- 代码模板库

#### 4. 项目实战
- 项目库
- 项目创建
- 项目分享社区
- 作品展示
- 点赞和评论
- Remix 功能

#### 5. 练习评测
- 题库管理
- 自动评测
- 错题本
- 智能推题
- 通关模式
- 实时排行榜

#### 6. 教学管理
- 班级管理
- 作业发布
- 作业批改
- 学情分析
- 教学日历
- 课堂互动

#### 7. AI 辅助
- 智能提示
- 代码纠错
- 学习路径推荐
- 虚拟助教
- 代码解释

#### 8. 游戏化激励
- 积分系统
- 徽章成就
- 等级体系
- 排行榜
- 每日任务
- 活动赛事

#### 9. 社交社区
- 作品分享
- 学习圈子
- 话题讨论
- 好友系统
- 私信功能

#### 10. 支付系统
- 课程购买
- 会员订阅
- 优惠券
- 团购拼课
- 退款管理

#### 11. 数据分析
- 学习数据统计
- 用户行为分析
- 教学效果评估
- 运营数据看板

#### 12. 运营管理
- 内容管理（CMS）
- 活动管理
- 消息推送
- 客服系统
- 问卷调查

## 教程资源

详见 [教程资源文档](./docs/tutorials.md)

### 视频教程

#### 中文资源
- **哔哩哔哩**
  - [编程启蒙课程](https://www.bilibili.com/)
  - [Scratch 入门教程](https://www.bilibili.com/)
  - [Python 少儿编程](https://www.bilibili.com/)

- **慕课网**
  - 前端开发课程
  - 后端开发课程
  - 全栈项目实战

#### 英文资源
- **YouTube**
  - [Code.org 官方教程](https://www.youtube.com/@codeorg)
  - [Scratch 教程](https://www.youtube.com/@ScratchTeam)
  - [freeCodeCamp](https://www.youtube.com/@freecodecamp)

### 图文教程

- **官方文档**
  - [React 官方文档](https://react.dev/)
  - [Vue 官方文档](https://vuejs.org/)
  - [Python 官方教程](https://docs.python.org/)

- **博客平台**
  - [掘金](https://juejin.cn/)
  - [CSDN](https://www.csdn.net/)
  - [Medium](https://medium.com/)

### 编程挑战

- **[LeetCode](https://leetcode.com/)**：算法刷题
- **[CodeWars](https://www.codewars.com/)**：编程挑战
- **[HackerRank](https://www.hackerrank.com/)**：技能认证
- **[洛谷](https://www.luogu.com.cn/)**：OI 竞赛平台
- **[牛客网](https://www.nowcoder.com/)**：编程练习

## 学习路线

详见 [学习路线文档](./docs/learning-path.md)

### 小学阶段（6-12 岁）

#### 低年级（1-3 年级）
1. **Scratch Jr**（6-7 岁）
   - 基础图形化编程
   - 简单动画制作
   - 故事创作

2. **Scratch**（7-9 岁）
   - 进阶图形化编程
   - 游戏开发入门
   - 项目创作

#### 高年级（4-6 年级）
1. **Python 入门**（9-10 岁）
   - 基础语法
   - 海龟绘图
   - 简单游戏

2. **Web 基础**（10-12 岁）
   - HTML/CSS 基础
   - JavaScript 入门
   - 网页制作

### 初中阶段（12-15 岁）

1. **算法基础**
   - 数据结构入门
   - 基础算法
   - OI 竞赛入门

2. **进阶开发**
   - Python 进阶
   - Web 开发
   - 移动应用开发

### 高中阶段（15-18 岁）

1. **竞赛方向**
   - NOI / NOIP
   - ACM / ICPC
   - 信息学竞赛

2. **工程方向**
   - 全栈开发
   - 项目实战
   - 开源贡献

## 贡献指南

欢迎贡献！请查看 [CONTRIBUTING.md](./CONTRIBUTING.md) 了解详情。

### 如何贡献

1. Fork 本仓库
2. 创建特性分支 (`git checkout -b feature/AmazingFeature`)
3. 提交更改 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 开启 Pull Request

### 贡献内容

- 补充遗漏的资源
- 更新过时的信息
- 修正错误
- 改进文档结构
- 分享经验和案例

## 许可证

本项目采用 [MIT License](LICENSE) 许可证。

## 联系方式

- 作者：zhaotoday
- 邮箱：6421664@qq.com
- GitHub：[@zhaotoday](https://github.com/zhaotoday)

## 致谢

感谢所有为编程教育事业做出贡献的组织和个人。

---

⭐ 如果这个项目对您有帮助，请给一个 Star！

📝 最后更新：2025-01-13
