---
theme: seriph
background: https://cover.sli.dev
class: text-center
highlighter: shiki
lineNumbers: false
info: |
  ## AI 编程分享
drawings:
  persist: false
transition: slide-left
title: AI 编程分享 - Day 1
---

# AI编程入门篇

无代码基础人群如何上手AI编程
 
---
layout: section
---

# 学习编程的好处 

---
layout: two-cols
---

<v-clicks>

## 💰 赚钱机会

- up主开发App，登上排行榜第一

<img src="https://s2.loli.net/2025/03/16/QmhuHRzvI5litns.png" style="height:35%;" alt="up主开发app，登上排行榜第一">

</v-clicks>

::right::

<v-clicks> 

## ⚡ 提高效率

- 李笑来使用Python写书

![李笑来《把时间当作朋友》](https://s2.loli.net/2025/03/16/Lx9Zv6OsElNTFI3.png) 
 
</v-clicks>

<div class="absolute bottom-10 left-0 right-0 text-center">AI编程工具的出现，让技术平权，让普通人可以入场开发自己的App！</div>

--- 
layout: section
---

# 学习编程的疑问

<v-clicks> 

## 难不难？

## 学什么？

## 怎么学？

</v-clicks> 

---
layout: section
---

# 难不难

<v-clicks> 

  AI正在重塑计算机教育，抛弃以往的学习模式
  
  就像现在你不需要学习如何使用算盘
  
  只要有计算器、能看懂数字、会加减乘除就可以计算一样。

</v-clicks> 


---
layout: section
---

# 学什么？

---
layout: two-cols
---

# Python

<v-clicks>

## 简单易学
- 接近英语语法 
- 丰富的库和框架
- 强大的社区支持
- 强大的生态系统

## 应用广泛
- 网络爬虫
- 数据分析
- 自动化脚本

</v-clicks>

::right::

<div class="ml-4">
<v-clicks>

# JavaScript

## 多平台支持
- 小程序开发
- 浏览器应用
- 移动应用（iOS/Android）
- 桌面应用（Windows/Mac）

## 全栈开发
- 前端界面
- 后端服务

</v-clicks>
</div>


---
layout: section
---

# 怎么学？

---

# AI辅助学习方法

<v-clicks>

## 传统方式
- 视频教程
- 在线课程

## AI互动学习

```md
我想学习[X]。请按照二八法则(80-20原则)制定一个全面的学习计划,重点关注能让我开始构建项目的20%核心概念。

请将计划按周安排，总计[Y]周,每月周涵盖特定的学习主题。
在完成这[Y]周的核心学习后,请推荐5个难度递增的项目(从入门到到进阶),帮助我应用和拓展[X]的知识。

对于每个项目,请提供简要描述并列出它将帮助强化的关键概念请确保计划详细到足以让初学者跟随，同时也要有足够的挑战性来培养独立思考和解决问题的能力。
```

</v-clicks>

---
layout: section
---

# AI编程的演进

---

# 编程工具的四个阶段
<div class="grid grid-cols-2 gap-4">
  <div class="p-4">
<v-clicks>

## 1️⃣ 手写代码     
- 记事本    
- Vi编辑器     

</v-clicks>
  </div>

  <div class="p-4">
<v-clicks>

## 2️⃣ 集成环境
- VSCode
- IntelliJ IDEA
- 代码提示 

</v-clicks>
  </div>

<div class="p-4">
<v-clicks>

## 3️⃣ AI编程
- Cursor
- Trae
- 代码自动补全
- 自然语言生成代码

</v-clicks>
</div>

  <div class="p-4">
<v-clicks>

## 4️⃣ 自动编程
- AI程序员Devin
- 需求到部署的全流程自动化

</v-clicks>
  </div>
</div>

---
layout: section
---

# AI编程工具

---

# AI编程工具

<style>
.slidev-layout table {
  font-size: 12px;
}
</style>

| 工具 | 核心功能 | 语言支持 | AI模型 | 价格 | 特色 |
|------|---------|----------|---------|------|-------|
| Cursor | 智能补全、代码生成 | 多语言 | 自研 | $20/月 | VS Code集成 |
| Trae | AI代码生成、多模态 | 中英双语 | Claude 3.5 | 免费 | 全流程支持 |
| Windsurf | 深度代码理解 | 多语言 | 自研 | $15/月 | 依赖分析 |
| Bolt.new | 零门槛Web IDE | 多语言 | - | 部分免费 | 实时预览 |
| v0 | 前端框架支持 | 多语言 | - | - | UI组件预览 |
 
---
layout: section
---

# Trae深度解析

---

# 什么是Trae？

<v-clicks>

## 定义
- The Real AI Engineer
- 字节跳动推出的AI原生IDE
- 全流程开发代理

## 技术特点
- 多模态交互（语音、草图）
- 上下文感知
- 安全合规

## 里程碑
- 2023.6：首个AI独立开发上架应用
- 2024.1：获得可信AI认证

</v-clicks>

---

# Trae版本对比

| 对比维度 | 国内版 | 国际版 |
|----------|--------|--------|
| AI模型 | Doubao-1.5-pro | GPT-4o、Claude-3.7 |
| 官网 | trae.com.cn | trae.ai |
| 登录方式 | 手机号/掘金 | Google账号 |
| 特色功能 | 掘金社区集成 | 多语言支持 |
| 适用场景 | 本地化开发 | 国际化项目 |

---
layout: section
---

# 实战演示

---

# 项目实战

<v-clicks>

## 入门项目
1. 个人简历网站
2. 待办事项应用
3. 贪吃蛇游戏

## 互动环节
- 翻车预测：扣1=会翻车，扣0=不会翻车
- 你想做什么项目？

</v-clicks>