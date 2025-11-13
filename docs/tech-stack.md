# 技术栈

## 目录

- [前端技术](#前端技术)
- [后端技术](#后端技术)
- [数据库选型](#数据库选型)
- [代码执行引擎](#代码执行引擎)
- [DevOps 工具](#devops-工具)
- [AI / 机器学习](#ai--机器学习)
- [架构设计](#架构设计)

## 前端技术

### 框架选择

#### React 生态
- **React**：https://react.dev/
  - **版本**：18.x
  - **优势**：
    - 组件化开发
    - 虚拟 DOM 性能优化
    - 丰富的生态系统
    - 大型社区支持
  - **适用场景**：
    - 复杂交互界面
    - 单页应用（SPA）
    - 跨平台应用

- **Next.js**：https://nextjs.org/
  - **版本**：14.x
  - **特点**：
    - 服务端渲染（SSR）
    - 静态站点生成（SSG）
    - API Routes
    - 优秀的 SEO
  - **适用场景**：
    - 营销页面
    - 博客系统
    - 需要 SEO 的页面

- **React Native**：https://reactnative.dev/
  - **跨平台移动端开发**
  - iOS / Android 原生应用
  - 代码复用率高

#### Vue 生态
- **Vue 3**：https://vuejs.org/
  - **版本**：3.x（Composition API）
  - **优势**：
    - 渐进式框架
    - 易学易用
    - 优秀的中文文档
    - 双向数据绑定
  - **适用场景**：
    - 快速原型开发
    - 中小型项目
    - 团队 Vue 技术栈

- **Nuxt.js**：https://nuxt.com/
  - **版本**：3.x
  - **特点**：
    - Vue 的 SSR 框架
    - 自动路由
    - 模块化架构
  - **适用场景**：
    - SEO 友好应用
    - 服务端渲染需求

- **Uni-app**：https://uniapp.dcloud.net.cn/
  - **特点**：
    - 一套代码多端运行
    - 微信小程序 / H5 / App
    - Vue 语法
  - **适用场景**：
    - 跨端应用开发
    - 教育类小程序

#### Angular（可选）
- **Angular**：https://angular.io/
  - **版本**：17.x
  - **特点**：
    - 完整的企业级框架
    - TypeScript 原生支持
    - 依赖注入
  - **适用场景**：
    - 大型企业应用
    - 需要严格架构的项目

---

### UI 组件库

#### Material Design 系
- **Material-UI (MUI)**：https://mui.com/
  - **React 组件库**
  - Google Material Design
  - 丰富的组件
  - 定制化主题

- **Vuetify**：https://vuetifyjs.com/
  - **Vue 组件库**
  - Material Design
  - 响应式布局

#### Ant Design 系
- **Ant Design**：https://ant.design/
  - **React 组件库**
  - 企业级 UI 设计
  - 阿里巴巴开源
  - 完整的设计规范
  - 丰富的业务组件

- **Ant Design Vue**：https://antdv.com/
  - **Vue 版本**
  - 与 Ant Design 保持一致

#### Element 系
- **Element Plus**：https://element-plus.org/
  - **Vue 3 组件库**
  - 饿了么开源
  - 中文文档完善
  - 开箱即用

#### 其他推荐
- **Chakra UI**：https://chakra-ui.com/
  - React 组件库
  - 易用性极佳
  - 无障碍访问

- **Tailwind CSS**：https://tailwindcss.com/
  - 原子化 CSS 框架
  - 高度可定制
  - 快速开发

- **DaisyUI**：https://daisyui.com/
  - Tailwind CSS 组件库
  - 主题系统
  - 轻量级

---

### 图形化编程组件

#### Blockly
- **官方库**：https://developers.google.com/blockly
- **集成方式**：
  ```bash
  npm install blockly
  ```
- **特点**：
  - 高度可定制
  - 代码生成器
  - 多语言支持
- **应用**：
  - 自定义积木块
  - 工具箱配置
  - 主题定制

#### Scratch Blocks
- **GitHub**：https://github.com/scratchfoundation/scratch-blocks
- **特点**：
  - Scratch 3.0 积木库
  - 基于 Blockly
  - 儿童友好设计

#### 自研编程引擎（可选）
- **参考**：编程猫 Kitten
- **优势**：
  - 完全控制
  - 深度定制
  - 性能优化
- **劣势**：
  - 开发成本高
  - 维护复杂

---

### 代码编辑器组件

#### Monaco Editor
- **GitHub**：https://github.com/microsoft/monaco-editor
- **集成**：
  ```bash
  npm install monaco-editor
  ```
- **React 封装**：
  ```bash
  npm install @monaco-editor/react
  ```
- **特点**：
  - VS Code 同款
  - 智能补全
  - 语法高亮
  - 多语言支持
  - 差异对比

#### CodeMirror
- **官网**：https://codemirror.net/
- **版本**：6.x
- **特点**：
  - 轻量级
  - 高度可扩展
  - 移动端友好
  - 主题丰富

#### Ace Editor
- **官网**：https://ace.c9.io/
- **特点**：
  - 高性能
  - 100+ 语言
  - 主题定制

---

### 状态管理

#### React 状态管理
- **Redux Toolkit**：https://redux-toolkit.js.org/
  - 官方推荐
  - 简化 Redux 使用
  - DevTools 支持

- **Zustand**：https://github.com/pmndrs/zustand
  - 轻量级
  - 简单易用
  - TypeScript 友好

- **Jotai**：https://jotai.org/
  - 原子化状态
  - React Hooks 风格

#### Vue 状态管理
- **Pinia**：https://pinia.vuejs.org/
  - Vue 3 官方推荐
  - 替代 Vuex
  - TypeScript 支持
  - 组合式 API

---

### 构建工具

#### Vite
- **官网**：https://vitejs.dev/
- **特点**：
  - 极速启动
  - 热模块替换（HMR）
  - 开箱即用
  - 现代化构建
- **推荐使用**：新项目首选

#### Webpack
- **官网**：https://webpack.js.org/
- **特点**：
  - 成熟稳定
  - 生态丰富
  - 高度可配置
- **适用**：复杂项目配置

#### Turbopack（新兴）
- **官网**：https://turbo.build/pack
- **特点**：
  - Vercel 开发
  - Rust 编写
  - 极速构建

---

### 其他前端工具

#### 图表可视化
- **ECharts**：https://echarts.apache.org/
  - 功能强大
  - 配置丰富
  - 中文文档

- **D3.js**：https://d3js.org/
  - 数据驱动
  - 高度定制

- **Chart.js**：https://www.chartjs.org/
  - 简单易用
  - 响应式

#### 动画库
- **Framer Motion**：https://www.framer.com/motion/
  - React 动画库
  - 声明式 API
  - 手势支持

- **GSAP**：https://greensock.com/gsap/
  - 高性能动画
  - 复杂动画序列

#### 拖拽库
- **react-dnd**：https://react-dnd.github.io/react-dnd/
  - React 拖拽
  - 灵活可扩展

- **dnd-kit**：https://dndkit.com/
  - 现代拖拽工具
  - 无障碍访问

---

## 后端技术

### 语言和框架选择

#### Node.js 生态

##### Express
- **官网**：https://expressjs.com/
- **特点**：
  - 轻量级
  - 中间件机制
  - 路由系统
  - 快速开发
- **适用场景**：
  - API 服务
  - 中小型项目
  - 快速原型

##### Nest.js
- **官网**：https://nestjs.com/
- **特点**：
  - 企业级框架
  - TypeScript 原生
  - 模块化架构
  - 依赖注入
  - 支持微服务
- **适用场景**：
  - 大型项目
  - 微服务架构
  - 团队协作

##### Koa
- **官网**：https://koajs.com/
- **特点**：
  - Express 团队开发
  - async/await
  - 轻量灵活
- **适用场景**：
  - 定制化需求
  - 中间件开发

---

#### Python 生态

##### Django
- **官网**：https://www.djangoproject.com/
- **版本**：5.x
- **特点**：
  - 全栈框架
  - ORM（Django ORM）
  - 自带管理后台
  - 用户认证系统
  - 安全性强
- **适用场景**：
  - 快速开发
  - 内容管理
  - 后台管理系统

##### FastAPI
- **官网**：https://fastapi.tiangolo.com/
- **特点**：
  - 高性能
  - 自动 API 文档
  - 类型检查
  - 异步支持
  - 现代化设计
- **适用场景**：
  - API 服务
  - 微服务
  - AI / ML 服务

##### Flask
- **官网**：https://flask.palletsprojects.com/
- **特点**：
  - 微框架
  - 轻量灵活
  - 易于扩展
  - 教学友好
- **适用场景**：
  - 小型项目
  - API 服务
  - 教学项目

---

#### Java 生态

##### Spring Boot
- **官网**：https://spring.io/projects/spring-boot
- **特点**：
  - 企业级框架
  - 微服务支持
  - 自动配置
  - 生态成熟
- **适用场景**：
  - 大型企业应用
  - 高并发系统
  - 金融级应用

##### Spring Cloud
- **官网**：https://spring.io/projects/spring-cloud
- **特点**：
  - 分布式系统
  - 服务发现
  - 配置中心
  - 负载均衡

---

### API 设计

#### RESTful API
- **规范**：
  - HTTP 方法（GET, POST, PUT, DELETE）
  - 资源命名
  - 状态码
  - 版本控制

#### GraphQL
- **官网**：https://graphql.org/
- **特点**：
  - 按需查询
  - 强类型
  - 单一端点
- **工具**：
  - Apollo Server
  - Apollo Client

#### gRPC
- **官网**：https://grpc.io/
- **特点**：
  - 高性能
  - Protocol Buffers
  - 双向流
- **适用场景**：
  - 微服务通信
  - 高性能 RPC

---

### 身份认证

#### JWT（JSON Web Token）
- **库**：
  - `jsonwebtoken` (Node.js)
  - `PyJWT` (Python)
- **特点**：
  - 无状态
  - 跨域支持
  - 移动端友好

#### OAuth 2.0
- **适用场景**：
  - 第三方登录
  - 授权服务
- **实现**：
  - Passport.js (Node.js)
  - Authlib (Python)

#### Session-based
- **特点**：
  - 传统方案
  - 服务端存储
  - 安全性高

---

## 数据库选型

### 关系型数据库

#### MySQL
- **官网**：https://www.mysql.com/
- **版本**：8.x
- **特点**：
  - 开源免费
  - 性能优秀
  - 社区活跃
  - 生态丰富
- **适用场景**：
  - 用户数据
  - 课程信息
  - 订单系统

#### PostgreSQL
- **官网**：https://www.postgresql.org/
- **特点**：
  - 功能强大
  - 支持 JSON
  - 扩展性强
  - ACID 完整性
- **适用场景**：
  - 复杂查询
  - 地理数据
  - 全文搜索

---

### 非关系型数据库

#### MongoDB
- **官网**：https://www.mongodb.com/
- **特点**：
  - 文档数据库
  - 灵活 Schema
  - 水平扩展
  - JSON 格式
- **适用场景**：
  - 用户作品
  - 学习记录
  - 日志数据

#### Redis
- **官网**：https://redis.io/
- **特点**：
  - 内存数据库
  - 高性能
  - 丰富数据类型
  - 持久化支持
- **适用场景**：
  - 缓存
  - 会话存储
  - 排行榜
  - 消息队列

---

### ORM / ODM

#### TypeORM（Node.js + TypeScript）
- **官网**：https://typeorm.io/
- **支持**：MySQL, PostgreSQL, MongoDB 等
- **特点**：
  - TypeScript 支持
  - 实体映射
  - 迁移管理

#### Prisma（Node.js）
- **官网**：https://www.prisma.io/
- **特点**：
  - 现代化 ORM
  - 类型安全
  - 自动生成客户端
  - 数据库迁移

#### Mongoose（MongoDB + Node.js）
- **官网**：https://mongoosejs.com/
- **特点**：
  - Schema 定义
  - 数据验证
  - 中间件

#### SQLAlchemy（Python）
- **官网**：https://www.sqlalchemy.org/
- **特点**：
  - Python ORM 标准
  - 灵活强大
  - 支持多数据库

---

## 代码执行引擎

### 在线评测系统

#### Judge0
- **GitHub**：https://github.com/judge0/judge0
- **官网**：https://judge0.com/
- **特点**：
  - 60+ 语言支持
  - RESTful API
  - Docker 隔离
  - 安全沙箱
- **部署**：
  - Docker Compose
  - 可扩展架构

#### 自研沙箱
- **技术方案**：
  - **Docker 容器隔离**
  - **资源限制**（CPU、内存、时间）
  - **网络隔离**
  - **文件系统只读**
- **实现参考**：
  - `isolate`（Linux 沙箱）
  - DMOJ Judge

---

### 代码执行流程

```
用户提交代码
    ↓
代码验证（语法、长度）
    ↓
放入执行队列
    ↓
分配执行容器
    ↓
编译（如需要）
    ↓
运行测试用例
    ↓
收集结果
    ↓
返回用户
```

---

## DevOps 工具

### 容器化

#### Docker
- **官网**：https://www.docker.com/
- **用途**：
  - 应用容器化
  - 开发环境一致性
  - 代码执行隔离
- **配置文件**：
  - `Dockerfile`
  - `docker-compose.yml`

#### Kubernetes（K8s）
- **官网**：https://kubernetes.io/
- **用途**：
  - 容器编排
  - 自动扩缩容
  - 服务发现
  - 负载均衡
- **适用场景**：
  - 大规模部署
  - 微服务架构

---

### CI/CD

#### GitHub Actions
- **官网**：https://github.com/features/actions
- **特点**：
  - 与 GitHub 集成
  - 免费额度
  - 丰富的 Actions 市场
- **用途**：
  - 自动测试
  - 自动部署
  - 代码检查

#### GitLab CI/CD
- **官网**：https://docs.gitlab.com/ee/ci/
- **特点**：
  - 内置 CI/CD
  - Pipeline 可视化
  - 自托管支持

#### Jenkins
- **官网**：https://www.jenkins.io/
- **特点**：
  - 老牌 CI/CD
  - 插件丰富
  - 高度可定制

---

### 监控和日志

#### 监控系统

##### Prometheus
- **官网**：https://prometheus.io/
- **特点**：
  - 时序数据库
  - 指标收集
  - 告警规则
- **可视化**：Grafana

##### Grafana
- **官网**：https://grafana.com/
- **特点**：
  - 数据可视化
  - 仪表盘
  - 多数据源支持

#### 日志系统

##### ELK Stack
- **Elasticsearch**：搜索和分析
- **Logstash**：日志收集
- **Kibana**：可视化

##### Loki
- **官网**：https://grafana.com/oss/loki/
- **特点**：
  - 轻量级
  - 与 Grafana 集成

---

### 错误追踪

#### Sentry
- **官网**：https://sentry.io/
- **特点**：
  - 错误监控
  - 性能监控
  - 多语言支持
  - 开源自托管

---

## AI / 机器学习

### AI 辅助编程

#### OpenAI API
- **官网**：https://platform.openai.com/
- **应用**：
  - GPT-4 代码生成
  - 智能提示
  - 代码解释
  - 错误纠正

#### GitHub Copilot
- **集成**：
  - VS Code
  - JetBrains IDEs

---

### 机器学习框架

#### TensorFlow.js
- **官网**：https://www.tensorflow.org/js
- **特点**：
  - 浏览器端 ML
  - 预训练模型
  - 实时推理
- **应用**：
  - 图像识别
  - 语音识别
  - 姿态检测

#### PyTorch
- **官网**：https://pytorch.org/
- **特点**：
  - Python ML 框架
  - 动态计算图
  - 研究友好

---

### 自然语言处理

#### Hugging Face Transformers
- **官网**：https://huggingface.co/
- **应用**：
  - 文本分类
  - 情感分析
  - 代码理解

---

## 架构设计

### 单体架构
- **适用**：初期 / 小型项目
- **优势**：
  - 简单易开发
  - 部署方便
  - 调试容易
- **劣势**：
  - 扩展性差
  - 单点故障

### 微服务架构
- **适用**：大型 / 复杂项目
- **服务拆分**：
  - 用户服务
  - 课程服务
  - 评测服务
  - 支付服务
- **优势**：
  - 独立部署
  - 技术栈灵活
  - 易于扩展
- **挑战**：
  - 复杂度高
  - 分布式事务
  - 服务治理

### Serverless
- **平台**：
  - AWS Lambda
  - Vercel Functions
  - Cloudflare Workers
- **适用场景**：
  - 按需计算
  - 事件驱动
  - 低成本

---

### 推荐技术栈组合

#### 方案一：Node.js 全栈
```
前端：React + Next.js + TypeScript
UI：Ant Design / Material-UI
状态管理：Zustand / Redux Toolkit
编辑器：Monaco Editor / Blockly

后端：Nest.js + TypeScript
数据库：PostgreSQL + Redis
ORM：Prisma
代码执行：Judge0

部署：Docker + K8s
CI/CD：GitHub Actions
监控：Prometheus + Grafana
```

#### 方案二：Python 后端
```
前端：Vue 3 + Nuxt.js
UI：Element Plus
编辑器：CodeMirror / Blockly

后端：FastAPI / Django
数据库：MySQL + MongoDB + Redis
ORM：SQLAlchemy / Django ORM

部署：Docker + Docker Compose
CI/CD：GitLab CI
```

#### 方案三：轻量级快速开发
```
前端：React + Vite
UI：Tailwind CSS + DaisyUI
编辑器：Blockly

后端：Express + TypeScript
数据库：PostgreSQL + Redis
ORM：Prisma

部署：Vercel (前端) + Railway (后端)
```

---

📝 最后更新：2025-01-13
