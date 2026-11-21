# Design Engineer Study Plan

### 从 UI/UX Designer 到 Design Engineer

这是我的设计工程学习计划，记录从 UI/UX 设计逐步学习前端开发、设计系统工程化和产品开发的过程。

我是一名 UI/UX 设计师，希望进一步拓展工程能力，将设计与代码结合起来。

我的职业目标是成为一名 Design Engineer（设计工程师），不仅能够完成数字产品的界面与交互设计，还能够通过代码实现设计，并理解产品的技术架构与开发流程。

这个仓库用于记录每日学习内容、代码练习、项目成果、技术问题和阶段性总结。

---

## 🎯 学习目标

- **设计系统工程化（Design System Engineering）**：掌握 Design Tokens 与 Design System 的设计、构建及工程化实现，将设计规范转化为可复用的代码组件。
- **创意编程与交互实现（Creative Coding & Interaction）**：学习使用代码实现具有创意和视觉表现力的交互动效，并将其应用于真实网站。
- **前端工程实践（Frontend Engineering）**：理解前端应用的整体架构与开发流程，能够将设计系统与交互动效整合到实际 Web 产品中。

---

## 🗺️ 100 天学习路线

| 阶段 | 时间 | 学习方向 | 阶段成果 |
|---|---|---|---|
| 01 | Day 01–03 | Web 工作原理与前端整体架构 | 第一个部署上线的网站 |
| 02 | Day 04–13 | 设计系统基础与 Design Tokens | Keats UI v0.1 |
| 03 | Day 14–25 | HTML、CSS 与响应式开发 | Keats UI Website |
| 04 | Day 26–35 | JavaScript 基础 | Interactive Dashboard |
| 05 | Day 36–55 | React 与 TypeScript | React 组件合集 |
| 06 | Day 56–70 | 设计系统工程化 | Keats UI v1.0 |
| 07 | Day 71–80 | 产品交互工程 | Product Interaction Lab |
| 08 | Day 81–83 | 创意编程与动效工程 | Creative Coding & Motion Showcase |
| 09 | Day 84–100 | 产品开发与作品集 | Web App MVP |

---

## 📅 每日学习进度

每天学习新的工程知识，并完成一个可以运行、展示或验证的作品。

每个学习日记录学习内容、代码实现、遇到的问题和 GitHub 产出。

完成当天任务后，将状态从 `⬜` 修改为 `✅`。

---

## Phase 01 — 前端整体架构

**Day 01–03**

目标：理解一个网站从代码编写、本地运行到部署上线的完整流程。

| Day | 学习主题 | GitHub 产出 | 状态 |
|---|---|---|---|
| 01 | Web 工作原理：浏览器、服务器、HTTP、HTML、CSS、JavaScript | My First Website：手写一个简单网站，并绘制 Web 工作原理图 | ⬜ |
| 02 | 前端项目架构：Pages、Layouts、Components、Routing、Assets | Website Architecture Demo：创建 Home、About、Projects 三个页面，展示目录结构和页面跳转 | ⬜ |
| 03 | 前端工程流程：Node.js、npm、Vite、Git、GitHub、Build、Deployment | First Deployed Website：使用 Vite 组织项目、上传 GitHub 并部署网站 | ⬜ |

**阶段成果：**

能够理解网站如何运行、前端项目如何组织，以及如何将本地代码部署到线上。

---

## Phase 02 — 设计系统基础

**Day 04–13**

目标：将 Figma 中的设计规范转化为能够在代码中使用的 Design Tokens，建立 Keats UI 的基础视觉体系。

| Day | 学习主题 | GitHub 产出 | 状态 |
|---|---|---|---|
| 04 | Design System Architecture：设计系统组成、Foundations、Tokens、Components、Patterns | Design System Architecture：绘制 Keats UI 结构图，建立项目目录和介绍页面 | ⬜ |
| 05 | Design Tokens：Primitive Tokens、Semantic Tokens、命名规则、JSON 基础 | Token Architecture：创建 `tokens.json`，定义第一套基础 Token | ⬜ |
| 06 | Color System：品牌色、中性色、语义色、CSS Variables | Color Tokens：制作颜色系统展示页，并让颜色引用 CSS 变量 | ⬜ |
| 07 | Typography System：字体、字号、字重、行高、排版层级 | Typography Tokens：制作 Heading、Body、Caption 等排版规范展示页 | ⬜ |
| 08 | Spacing System：间距比例、Spacing Scale、CSS 单位、Box Model | Spacing Tokens：制作间距规范展示页，使用 CSS 变量控制间距 | ⬜ |
| 09 | Shape & Elevation：圆角、边框、阴影、层级 Tokens | Shape Tokens：完成圆角、边框与阴影的视觉规范展示 | ⬜ |
| 10 | Semantic Tokens：Primitive 与 Semantic 的映射、Light/Dark Theme | Semantic Token System：通过 CSS 变量实现明暗主题切换 | ⬜ |
| 11 | Component Architecture：组件结构、Slots、Variants、States、命名规范 | Component Anatomy：制作组件结构、变体与状态的可视化展示 | ⬜ |
| 12 | CSS Organization：CSS 文件组织、样式复用、全局样式、选择器优先级 | CSS Architecture：整理 Keats UI 样式结构，将 Tokens 与组件样式分离 | ⬜ |
| 13 | Design System Documentation：规范文档、使用说明、版本管理 | Keats UI v0.1：发布第一版 Design System Foundations 文档与展示网站 | ⬜ |

**阶段成果：Keats UI v0.1**

包含颜色、字体、间距、圆角、阴影等基础规范，以及 Primitive Tokens 和 Semantic Tokens。

---

## Phase 03 — HTML & CSS 工程实践

**Day 14–25**

目标：学习网页布局、响应式设计和 CSS 工程组织，并将 Keats UI 设计规范应用到真实网站中。

| Day | 学习主题 | GitHub 产出 | 状态 |
|---|---|---|---|
| 14 | Semantic HTML：HTML 语义化、文档结构、页面层级、可访问性基础 | Semantic Website：创建具有完整语义结构的网站首页 | ⬜ |
| 15 | CSS Box Model：Width、Height、Padding、Margin、Border、Box Sizing | Layout Fundamentals：制作盒模型可视化实验页面 | ⬜ |
| 16 | Flexbox：主轴、交叉轴、对齐、弹性布局 | Flexbox Layout：实现 Header、Navigation、Card List 等布局 | ⬜ |
| 17 | CSS Grid：网格布局、Columns、Rows、Gap | Dashboard Layout：实现 Sidebar、Header、Main Content 布局 | ⬜ |
| 18 | CSS Positioning：Relative、Absolute、Fixed、Sticky、Z-index | Sticky Layout：实现固定导航及粘性侧边栏 | ⬜ |
| 19 | Responsive Design：Media Queries、Breakpoints、流式布局 | Responsive Landing Page：完成 Desktop、Tablet、Mobile 响应式页面 | ⬜ |
| 20 | CSS Architecture：变量、样式复用、组件样式、全局样式 | Token-driven Website：使用 Keats UI Tokens 统一网站样式 | ⬜ |
| 21 | Application Layout：Header、Sidebar、Main、Footer、共享布局 | Application Shell：建立可复用的应用布局 | ⬜ |
| 22 | Multi-page Website：多页面结构、导航、URL、资源路径 | Multi-page Portfolio：完成首页、项目列表和项目详情页 | ⬜ |
| 23 | CSS Components：Classes、Variants、基础组件样式复用 | CSS Component Collection：制作 Card、Badge、Button、Navigation 样式合集 | ⬜ |
| 24 | Design System Integration：将 Tokens 与组件样式应用到真实页面 | Keats UI Website Demo：搭建使用统一设计规范的多页面网站 | ⬜ |
| 25 | Website Release：DevTools 调试、响应式检查、代码整理、部署 | Keats UI v0.2：发布基于设计系统的完整响应式网站 | ⬜ |

**阶段成果：Keats UI v0.2**

能够使用 HTML/CSS 搭建完整网站，通过 Design Tokens 保持视觉一致性，并实现响应式布局。

---

## Phase 04 — JavaScript 基础

**Day 26–35**

目标：理解交互背后的程序逻辑，掌握 JavaScript、DOM、事件、状态和异步请求。

| Day | 学习主题 | GitHub 产出 | 状态 |
|---|---|---|---|
| 26 | JavaScript Fundamentals：变量、数据类型、运算符、函数、作用域 | JS Fundamentals Playground：制作基础 JavaScript 语法实验页 | ⬜ |
| 27 | Arrays & Objects：数组、对象、属性访问、对象解构、数据结构 | Data-driven Gallery：通过 JavaScript 数据动态生成卡片 | ⬜ |
| 28 | Conditions & Loops：条件判断、循环、函数组合 | Logic Playground：根据不同条件动态展示内容 | ⬜ |
| 29 | DOM Manipulation：DOM 树、元素查找、文本与属性更新 | DOM Playground：通过 JavaScript 动态修改网页内容 | ⬜ |
| 30 | JavaScript Events：Click、Input、Change、事件监听、事件传播 | Event Playground：制作包含多种事件响应的交互页面 | ⬜ |
| 31 | UI State：状态概念、状态对象、状态更新、界面同步 | Settings Panel：实现主题、布局和显示选项切换 | ⬜ |
| 32 | Array Methods：`map()`、`filter()`、`find()`、`sort()` | Search & Filter Gallery：实现列表搜索、筛选和排序 | ⬜ |
| 33 | JavaScript Modules：`import`、`export`、模块拆分 | Modular JavaScript App：将交互项目拆分成多个 JS 模块 | ⬜ |
| 34 | Async JavaScript：Promise、Async/Await、Fetch、错误处理 | API Data Viewer：请求公开 API，处理加载、成功与失败状态 | ⬜ |
| 35 | JavaScript Integration：综合 DOM、Events、State、Modules、Async | Interactive Dashboard v1：完成包含搜索、筛选及远程数据的 Dashboard | ⬜ |

**阶段成果：Interactive Dashboard**

能够使用原生 JavaScript 完成基本产品交互，并理解数据、状态和界面更新之间的关系。

---

## Phase 05 — React 与 TypeScript

**Day 36–55**

目标：从原生 HTML/CSS/JavaScript 进入现代前端组件化开发，掌握 React、TypeScript 和组件复用。

| Day | 学习主题 | GitHub 产出 | 状态 |
|---|---|---|---|
| 36 | React Architecture：React 的作用、组件树、声明式 UI | First React App：搭建 React 项目并绘制组件树 | ⬜ |
| 37 | JSX：JSX 语法、表达式、条件渲染、组件返回结构 | React Layout Demo：将静态 HTML 页面改写为 JSX | ⬜ |
| 38 | React Components：函数组件、组件拆分、组件职责与复用 | Reusable Components：拆分 Header、Sidebar、Card 等组件 | ⬜ |
| 39 | Props：组件属性、数据传递、默认值、组件配置 | Configurable Cards：通过 Props 生成不同内容与样式的卡片 | ⬜ |
| 40 | useState：State、重新渲染、状态更新、不可变数据 | Interactive Settings Panel：使用 React State 控制界面 | ⬜ |
| 41 | React Events：事件处理、状态切换、条件渲染 | Interactive Tabs：实现具有真实内容切换的 Tabs | ⬜ |
| 42 | Lists & Keys：数组渲染、Key、条件渲染 | Dynamic List：动态生成与更新列表 | ⬜ |
| 43 | Component Composition：Children、组件组合、布局复用 | Composable Layout：实现可组合的页面布局组件 | ⬜ |
| 44 | Shared State：状态提升、父子组件通信、数据流 | Shared State Dashboard：实现多个组件之间的状态联动 | ⬜ |
| 45 | React Routing：客户端路由、URL、嵌套路由、共享 Layout | Multi-page React App：完成具有独立 URL 的 React 网站 | ⬜ |
| 46 | TypeScript Basics：基础类型、类型推断、Union Types | TypeScript Playground：将基础 JS 示例改写为 TypeScript | ⬜ |
| 47 | Type & Interface：Interface、Type、可选属性、对象结构 | Typed Data Gallery：为列表数据建立类型定义 | ⬜ |
| 48 | Typed React Props：Props 类型定义、事件类型、组件类型 | Typed Card Components：实现带有 TypeScript 类型的组件 | ⬜ |
| 49 | Component API：Variants、Sizes、Props 设计、默认行为 | Configurable Button：实现可通过 Props 配置的按钮 | ⬜ |
| 50 | React Forms：受控输入、表单状态、表单验证 | React Form：完成一个具有验证逻辑的表单 | ⬜ |
| 51 | Custom Hooks：Hook 的作用、逻辑复用、自定义 Hook | Custom Hook Demo：实现并复用一个自定义 Hook | ⬜ |
| 52 | React Context：Context、Provider、跨组件状态共享 | Theme Provider：实现全站主题切换功能 | ⬜ |
| 53 | Data Fetching：React 异步请求、Loading、Error、数据更新 | React API Dashboard：将公开 API 数据接入 Dashboard | ⬜ |
| 54 | Refactoring：组件拆分、代码重构、复用与可维护性 | React Refactoring：重构之前的 Dashboard | ⬜ |
| 55 | React Release：整合 React、TypeScript、Routing、State、Tokens | Keats UI v0.3：发布 React + TypeScript 组件展示网站 | ⬜ |

**阶段成果：Keats UI v0.3**

能够理解 React 组件架构、Props、State 和组件通信，并为基础组件定义 TypeScript 类型。

---

## Phase 06 — 设计系统工程化

**Day 56–70**

目标：将 Keats UI 从视觉规范升级为可复用的 React + TypeScript 组件库。

| Day | 学习主题 | GitHub 产出 | 状态 |
|---|---|---|---|
| 56 | Component Library Architecture：组件库目录、公共组件、业务组件、Tokens 与组件关系 | Keats UI Architecture v1：建立组件库目录并绘制结构图 | ⬜ |
| 57 | Token Architecture：Primitive、Semantic、Component Tokens | Multi-layer Token System：升级多层级 Token 架构 | ⬜ |
| 58 | Token Integration：CSS Variables、主题映射、React 组件中的 Token 复用 | Token-driven React UI：让 React 组件统一使用 Tokens | ⬜ |
| 59 | Button System：Props、Variants、Sizes、Disabled、Loading | Button Component：开发完整的 React Button 组件 | ⬜ |
| 60 | Input System：Label、Help Text、Error、输入状态、组件 API | Input Component：开发可复用的 Input 组件 | ⬜ |
| 61 | Select Component：选择逻辑、选项数据、状态与键盘操作 | Select Component：实现可复用的基础 Select | ⬜ |
| 62 | Modal Component：Dialog、关闭逻辑、Esc、焦点管理 | Modal Component：实现具有基本可访问性的弹窗 | ⬜ |
| 63 | Tabs Component：选中状态、Tab 与 Panel 关联、ARIA、键盘导航 | Accessible Tabs：开发可访问的 Tabs 组件 | ⬜ |
| 64 | Feedback Components：Toast、Alert、Progress、Loading、异步反馈 | Feedback Components：完成反馈组件合集 | ⬜ |
| 65 | Navigation System：Navigation、Breadcrumb、Sidebar、Active State | Navigation Components：构建导航组件集 | ⬜ |
| 66 | Storybook：Stories、Controls、组件展示、文档结构 | Storybook Setup：为 Keats UI 建立 Storybook | ⬜ |
| 67 | Component Documentation：Props 文档、交互规范、使用场景、Do/Don't | Component Documentation：完成核心组件使用说明 | ⬜ |
| 68 | Accessibility：语义化、键盘导航、焦点、ARIA、WCAG 基础 | Accessibility Audit：检查并改进现有组件 | ⬜ |
| 69 | Component Testing：单元测试、交互测试、组件状态验证 | Component Tests：为 Button、Input、Tabs 编写基础测试 | ⬜ |
| 70 | Design System Release：代码整理、组件文档、版本发布 | Keats UI v1.0：发布 React + TypeScript Design System | ⬜ |

**阶段成果：Keats UI Design System v1.0**

包含：

- Figma 视觉与组件规范
- Design Tokens
- React + TypeScript 组件
- 组件 Variants 与 States
- Storybook 文档
- 基础可访问性支持
- 组件测试
- GitHub 源代码

---

## Phase 07 — 产品交互工程

**Day 71–80**

目标：从通用 UI 组件进入真实业务交互，学习复杂状态和产品功能的实现方式。

| Day | 学习主题 | GitHub 产出 | 状态 |
|---|---|---|---|
| 71 | Product State Management：业务状态、组件状态、派生状态、状态组织 | Product Workspace：建立具有多个状态的产品工作台 | ⬜ |
| 72 | Multi-step Form：多步骤表单、跨步骤数据、验证与提交逻辑 | Multi-step Form：完成多步骤表单 | ⬜ |
| 73 | Data Table：数据结构、排序、筛选、分页 | Interactive Data Table：实现可交互数据表格 | ⬜ |
| 74 | Search Experience：关键词搜索、防抖、搜索结果、Empty State | Search Interface：完成产品级搜索界面 | ⬜ |
| 75 | Drag & Drop：拖拽逻辑、状态反馈、数据更新、替代操作 | Kanban Board：实现可拖拽任务面板 | ⬜ |
| 76 | Command Palette：快捷键、搜索匹配、键盘导航、焦点管理 | Command Palette：实现命令搜索菜单 | ⬜ |
| 77 | File Management：File API、文件选择、预览、上传状态 | File Upload Manager：实现文件上传管理界面 | ⬜ |
| 78 | Async UI：Loading、Error、Retry、Empty、Success 状态 | Async State Playground：制作异步状态展示与交互实验 | ⬜ |
| 79 | Product Integration：多个业务模块的组合与联动 | Product Dashboard：整合搜索、数据表格与管理功能 | ⬜ |
| 80 | Product Release：代码优化、交互测试、性能检查、项目说明 | Product Interaction Lab v1.0：发布产品交互合集 | ⬜ |

**阶段成果：Product Interaction Lab**

包含数据表格、复杂表单、搜索、拖拽、文件管理等真实产品交互。

这一阶段尽量使用自己开发的 Keats UI 组件。

---

## Phase 08 — Creative Coding & Motion Engineering（创意编程与动效工程）

**Day 81–83**

目标：学习通过 CSS、JavaScript 和 GSAP 实现具有视觉表现力的交互动效，并掌握 Rive 与 React 的集成方法，将动效应用于真实网站和产品组件。

| Day | 学习主题 | GitHub 产出 | 状态 |
|---|---|---|---|
| 81 | CSS Animation & GSAP：学习 Keyframes、Transition、Easing、Timeline，理解 CSS 动画与 JavaScript 动画的区别 | Motion Playground：制作 CSS Animation 和 GSAP 动效实验，展示不同动画与缓动效果 | ⬜ |
| 82 | Interactive Motion：学习 Scroll-triggered Animation、Pointer Events、交互状态驱动动画 | Interactive Motion Demo：制作具有滚动触发动画与鼠标交互效果的网站展示区 | ⬜ |
| 83 | Rive × React Integration：学习 Rive Runtime、State Machine 与 React State 的联动、动画状态控制 | Rive React Component：实现一个由 React 状态驱动的 Rive 交互组件 | ⬜ |

**阶段成果：Creative Coding & Motion Showcase**

重点掌握：

- CSS Animation 与 GSAP 动画实现
- 滚动与鼠标驱动的交互效果
- React State 与 Rive State Machine 的联动
- 将动效应用于真实产品界面

---

## Phase 09 — 产品开发与作品集

**Day 84–100**

目标：开发并上线一个功能范围明确的 Web App MVP。

项目选择：**Reading App**

第一版主要包含文章阅读、文字选择、收藏、笔记、搜索及用户数据保存。

| Day | 学习主题 | GitHub 产出 | 状态 |
|---|---|---|---|
| 84 | Product Scope：MVP 范围控制、用户流程、功能优先级、技术选型 | Reading App PRD：建立简化需求文档、用户流程图和项目 README | ⬜ |
| 85 | Next.js Architecture：App Router、项目目录、Pages、Layouts、Routing | Reading App Architecture：搭建 Next.js 项目结构 | ⬜ |
| 86 | Application Layout：应用布局、共享导航、组件集成、设计系统复用 | Reading App Layout：完成应用主框架 | ⬜ |
| 87 | Reading Interface：阅读器布局、排版、滚动区域、文章内容渲染 | Reading Interface：完成文章阅读页面 | ⬜ |
| 88 | Article Management：文章数据结构、列表渲染、详情页路由 | Article Library：完成文章列表和详情页 | ⬜ |
| 89 | Text Selection：Selection API、选区范围、文本选择操作 | Text Selection Feature：实现选中文字后的操作入口 | ⬜ |
| 90 | Highlights & Notes：高亮数据模型、选区位置保存、笔记状态 | Highlight & Notes：完成基础高亮和笔记功能 | ⬜ |
| 91 | Database Architecture：数据库、表、主键、外键、数据关系 | Database Schema：设计文章、用户、收藏和笔记的数据表 | ⬜ |
| 92 | Supabase Integration：Supabase 客户端、数据读取、插入、更新、删除 | Database Integration：连接文章和笔记数据库 | ⬜ |
| 93 | Authentication：用户注册、登录、Session、访问权限 | Authentication Flow：完成登录与用户数据隔离 | ⬜ |
| 94 | Persistent Favorites：收藏数据持久化、用户关联、错误处理 | Favorites Feature：实现刷新后仍然保存的收藏功能 | ⬜ |
| 95 | Search：客户端搜索、数据库查询、关键词匹配 | Article Search：实现文章搜索功能 | ⬜ |
| 96 | API Integration：服务端 API、环境变量、密钥保护、异步请求 | AI Explanation Prototype：实现文本解释接口原型，必要时使用 Mock API | ⬜ |
| 97 | Error Handling：Loading、Error、Retry、Empty、Success | Product States：完善主要业务流程中的异常状态 | ⬜ |
| 98 | Accessibility & Performance：键盘导航、语义、性能分析与优化 | Product Optimization：完成阅读器的可访问性和性能改进 | ⬜ |
| 99 | Deployment & Release：Vercel 部署、环境变量、构建、线上检查 | Reading App v1.0：部署公开可访问的 MVP | ⬜ |
| 100 | Portfolio & Review：项目文档、技术选型、设计到代码、工程难点 | 100 Days Showcase：发布最终学习索引与 Design Engineer 案例说明 | ⬜ |

**阶段成果：Reading App v1.0**

目标是完成一条真实可用的用户流程：

登录 → 浏览文章 → 阅读 → 收藏或添加笔记 → 保存 → 再次登录后恢复数据。

AI 解释功能作为进阶内容，根据实际开发进度决定是否完成。

---

## 🛠️ 技术栈（Tech Stack）

### Frontend — 前端开发

- HTML5 / CSS3
- JavaScript
- TypeScript
- React
- Next.js

### Design & Interaction — 设计与交互

- Figma
- Design Tokens
- Storybook
- Rive

### Development Tools — 开发工具

- VS Code / Cursor
- Codex
- Git & GitHub
- Vite
- Chrome DevTools

### Backend & Deployment — 后端与部署

- Supabase
- Vercel

---

## 🧩 重点项目（Featured Projects）

### 01. Keats UI — Design System

从 Figma 设计规范出发，逐步构建一套基于 React 和 TypeScript 的可复用设计系统。

**学习重点：**

- Design Tokens
- Component Architecture
- Accessibility
- React + TypeScript
- Figma to Code
- Storybook Documentation

**Repository：** `keats-ui`

**状态：** 计划中

### 02. Product Interaction Lab

一个真实产品交互功能合集，包括数据表格、复杂表单、搜索、拖拽、文件上传和命令菜单等。

**学习重点：**

- UI Engineering
- State Management
- Complex Interaction Patterns
- Component Integration

**Repository：** `product-interaction-lab`

**状态：** 计划中

### 03. Creative Coding & Motion Showcase

通过 CSS Animation、JavaScript、GSAP 和 Rive 实现具有视觉表现力的交互动效，并探索将其应用到实际网站和 React 组件中的方法。

**学习重点：**

- CSS Animation
- GSAP
- Scroll-triggered Animation
- Pointer Events
- Rive Runtime
- React State Integration

**Repository：** `creative-coding-lab`

**状态：** 计划中

### 04. Reading App

一个具有文章阅读、文本选择、高亮、笔记、收藏和数据持久化功能的 Web 应用。

**学习重点：**

- Frontend Architecture
- React / Next.js
- Database Integration
- API
- Authentication
- End-to-end Product Development

**Repository：** `reading-app`

**状态：** 计划中

---

## 💡 我的学习方式（Learning Approach）

每天的学习遵循六个步骤：

1. **Learn — 学习**

   理解当天需要掌握的工程概念和技术知识。

2. **Design — 设计**

   分析页面、组件、交互或系统结构，明确实现目标。

3. **Build — 开发**

   使用代码和 AI 辅助工具实现当天的作品。

4. **Understand — 理解**

   阅读核心代码，理解实现原理，并独立修改关键部分。

5. **Debug — 调试**

   检查功能、定位问题、优化实现。

6. **Share — 发布**

   将作品上传 GitHub，记录学习心得和技术问题。

Codex 等 AI 工具是开发辅助工具，学习目标是逐步建立能够独立理解、评估、修改和维护代码的工程能力。

---

## ✅ 学习原则（Learning Principles）

- 每天完成一个具体、可以验证的学习成果。
- 注重理解代码，而不只是生成代码。
- 优先学习可复用、可维护的工程实现方式。
- 将响应式与可访问性作为基础要求。
- 通过设计系统连接视觉设计与工程开发。
- 记录错误、解决过程和改进经验。
- 每天尽量保留独立编码练习。
- 不为了连续打卡而牺牲学习质量。
- 持续完善长期项目，而不是每天都创建全新项目。

---

## ⏱️ 每日学习时间

计划每天投入约 5–6 小时。

| 学习环节 | 时间 | 具体任务 |
|---|---|---|
| 理论学习 | 60 分钟 | 理解工程概念和当天的新知识 |
| 设计与架构拆解 | 45 分钟 | 分析页面、组件、数据流或结构 |
| Codex 辅助开发 | 90 分钟 | 实现当天项目 |
| 独立编码 | 60 分钟 | 独立编写或修改关键逻辑 |
| 调试与测试 | 45 分钟 | 使用 DevTools 检查并修复问题 |
| GitHub 发布 | 30 分钟 | 提交代码、截图和学习总结 |
| **总计** | **5.5 小时** | |

实际学习时间根据当天任务的难度适当调整。

---

## 📂 GitHub 仓库结构

主仓库：

`100-days-of-design-engineering`

用于集中记录学习路线、每日进度和技术成长。

    100-days-of-design-engineering/
    ├── README.md
    ├── day-01-my-first-website/
    ├── day-02-website-architecture/
    ├── day-03-first-deployed-website/
    ├── ...
    └── learning-notes/

较大型的长期项目使用独立仓库：

- `keats-ui`
- `product-interaction-lab`
- `creative-coding-lab`
- `reading-app`

主仓库的每日进度表将逐步添加对应的源码、演示或项目链接。

---

## 🏁 学习里程碑（Milestones）

| Day | 里程碑 | 预期能力 |
|---|---|---|
| 03 | 理解前端开发流程 | 理解网站的构建、运行与部署 |
| 13 | 完成第一套 Design Tokens | 能将视觉规范映射为代码变量 |
| 25 | 完成响应式网站 | 能使用 HTML/CSS 和 Tokens 构建网页 |
| 35 | 完成 JavaScript 交互项目 | 能理解事件、状态和数据驱动的 UI |
| 55 | 掌握 React + TypeScript 基础 | 能开发具有明确 Props 和 State 的组件 |
| 70 | 发布 Keats UI v1.0 | 能构建可复用的 React 设计系统 |
| 80 | 完成 Product Interaction Lab | 能实现常见复杂产品交互 |
| 83 | 完成 Creative Coding & Motion Showcase | 能使用代码实现交互动效，并将 Rive 与 React 集成 |
| 99 | 部署 Web App MVP | 能开发并上线具有数据功能的 Web 产品 |
| 100 | 发布最终作品集总结 | 完成学习复盘与 Design Engineer 项目案例 |

---

## 📌 最终目标（Final Goal）

通过这 100 天，从主要使用 Figma 设计界面的 UI/UX Designer，逐步建立 Design Engineer 所需的前端工程能力。

具体包括：

- 理解数字产品的整体架构。
- 构建可复用、可维护的设计系统。
- 将视觉与交互设计转化为代码组件。
- 开发具有实际功能的 Web 应用。
- 建立设计与工程结合的完整工作流程。
