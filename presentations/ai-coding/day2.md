---
theme: seriph
background: https://cover.sli.dev
class: text-center
highlighter: shiki
lineNumbers: false
info: |
  ## AI 编程
drawings: false
persist: false
transition: slide-left
title: AI 编程 
---

# AI Coding

<div class="text-xl mt-4 opacity-80">
0基础人群如何上手 AI 编程
</div>




---
layout: two-cols
---

<v-clicks >

# 什么是编程？🤔

<div style="position: absolute; top: 90%; left: 50%; transform: translate(-50%, -50%);width:90%;text-align:center;">编程就是编写程序的过程，是将人类思维和指令转化为计算机可以理解和执行的语言</div>

### 把一个具体的动作抽象出来​

写一个爬虫的逻辑​：
1. 引入请求库​
2. 获取标题​
3. 打印标题 
4. ...

</v-clicks>
::right::
<v-clicks>

``` python {monaco-run}
import requests
from bs4 import BeautifulSoup

# 目标网页的URL
url = 'http://example.com'

# 发送HTTP请求
response = requests.get(url)
response.encoding = 'utf-8'  # 根据网页的编码方式进行设置

# 检查请求是否成功
if response.status_code == 200:
    # 使用BeautifulSoup解析HTML内容
    soup = BeautifulSoup(response.text, 'html.parser')
    
    # 提取网页的标题
    title = soup.find('title').get_text()
    
    # 打印标题
    print('网页标题为: ', title)
else:
    print('请求失败，错误码：', response.status_code)
```

</v-clicks>

---


<v-clicks>

## 编程语言的发展

- 机器听不懂人话，所以需要和机器沟通，就需要编程语言，比如java、JavaScript、Python、C#..​

- 编程语言发展：机器语言→汇编语言→高级语言→自然语言​

- 有了AI之后，让AI充当翻译，帮我去和机器沟通​

</v-clicks>

---
layout: center
---



# 为什么要学习编程？ 🤔

<v-clicks>

- 提升个人竞争力
- 实现自动化和效率提升
- 创造额外收入机会
- 开拓职业发展新方向

</v-clicks>

---
layout: two-cols
---

<v-clicks>

# 💰 赚钱机会

- up 主开发 App，登上排行榜第一

<img src="https://s2.loli.net/2025/03/17/PEOnXeuLzFi93l5.png" style="height:35%;" alt="up主开发app，登上排行榜第一">



</v-clicks>

::right::

<v-clicks>

# ⚡ 提高效率

- 李笑来使用 Python 写书
 
<img src="https://s2.loli.net/2025/03/16/Lx9Zv6OsElNTFI3.png" style="height:35%;" alt="up主开发app，登上排行榜第一">


</v-clicks>
 
---
layout: center
---

# 学习编程的疑问

<v-clicks>

- 难不难？
- 学什么？
- 怎么学？

</v-clicks>

---
layout: center
---


# 难不难

<v-clicks>

- AI 正在重塑计算机教育，抛弃以往的学习模式
- 就像现在你不需要学习如何使用算盘
- 只要有计算器、能看懂数字、会加减乘除就可以计算一样

</v-clicks>
 
---
layout: center
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
layout: center
---


# 怎么学？

---

# AI 辅助学习方法

<v-clicks>

## 传统方式

- 视频教程
- 在线课程

## AI 互动学习

提示词：

```md
我想学习[X]。请按照二八法则(80-20 原则)制定一个全面的学习计划,重点关注能让我开始构建项目的 20%核心概念。

请将计划按周安排，总计[Y]周,每月周涵盖特定的学习主题。
在完成这[Y]周的核心学习后,请推荐 5 个难度递增的项目(从入门到到进阶),帮助我应用和拓展[X]的知识。

对于每个项目,请提供简要描述并列出它将帮助强化的关键概念请确保计划详细到足以让初学者跟随，同时也要有足够的挑战性来培养独立思考和解决问题的能力。
```

</v-clicks>
 
---
layout: center
---

# 编程的演进

---

# 编程工具的四个阶段

<div class="grid grid-cols-2 gap-4">
  <div class="p-4">
<v-clicks>

## 1️⃣ 手写代码

- 记事本
- Vi 编辑器

</v-clicks>
  </div>
  <div class="p-4">
<v-clicks>

## 2️⃣ IDE 时代

- VSCode
- IntelliJ IDEA
- 代码提示
<!-- 集成开发环境=简称IDE，类似我们写ppt，需要使用WPS一样，文件的后缀名同理。 -->

</v-clicks>
  </div>

<div class="p-4">
<v-clicks>

## 3️⃣ AI 编程时代

- Cursor
- Trae
- 代码自动补全
- 自然语言生成代码

</v-clicks>
</div>

  <div class="p-4">
<v-clicks>

## 4️⃣ 未来

- AI 程序员 Devin
- 需求到部署的全流程自动化

</v-clicks>
  </div>
</div>

---
layout: center
---

# AI 编程工具一览

---
 

# AI快速构建工具
 
 <style>
.slidev-layout table {
  font-size: 12px;
}
</style> 

| 工具 | 核心功能 | 语言支持 | AI 模型 | 价格 | 特色 |
|------|----------|----------|---------|------|------|
| Bolt.new | 零门槛 Web IDE，全栈开发 | 多语言支持 | 未明确 | 免费版（有限访问）<br>专业版 $20/月 | 实时预览、一键部署、对话式开发 |
| v0 | 前端框架支持、UI 组件生成 | 多语言支持 | 未明确 | 免费版（基础功能）<br>专业版 $20/月 | UI 组件预览、实时代码调整 |
| Builder.io | 可视化页面构建、组件生成 | 支持多种前端框架 | 专有AI模型 | 免费版（有限功能）<br>团队版 $29/月起 | 无代码编辑器、AI设计建议、多平台发布 |
| GitHub Copilot Studio | 应用原型快速构建 | 多语言支持 | OpenAI模型 | $19/月/用户 | 代码库理解、自定义AI助手、团队协作 |
 
<br>

- 加速开发流程 : AI自动生成代码，显著减少手动编程时间
- 降低技术门槛 : 零代码环境让非专业人士也能参与开发
- 实时预览调整 : 即时查看更改效果，快速迭代设计
- 简化部署流程 : 一键部署功能缩短上线时间


---

# 代码助手

 
| 工具 | 核心功能 | 语言支持 | AI 模型 | 价格 | 特色 |
|------|----------|----------|---------|------|------|
| 通义灵码 | 代码补全、代码生成、智能问答 | 多语言支持，包括Python、Java、JavaScript等 | 通义大模型 | 免费（阿里云生态） | 中文支持优秀、与阿里云服务深度集成、代码解释能力强 |
| Marscode | 代码生成、智能补全、代码转换 | 多语言支持 | 火山引擎大模型 | 免费（字节跳动生态） | 中文支持良好、字节跳动技术栈集成、代码重构能力 |
| CodeGeeX | 代码生成、补全、注释生成 | 支持20+编程语言 | CodeGeeX (开源) | 基础版免费，专业版付费 | 开源模型、离线使用、中文支持良好 |
| GitHub Copilot | 实时代码建议、函数生成、注释转代码 | 支持多种主流编程语言 | OpenAI Codex | $10/月或$100/年，学生免费 | 强大的上下文理解、IDE集成度高、持续更新 | 
  

1. **智能代码生成**：自动补全代码，减少手动编写工作量。
2. **多语言支持**：兼容各种编程语言，适用范围广。
3. **提升开发效率**：加速编程过程，缩短项目周期。
4. **开发环境无缝集成**：与IDE完美融合，操作便捷。
5. **降低编程门槛**：简化复杂任务，帮助新手快速上手。

---

# AI IDE

<style>
.slidev-layout table {
  font-size: 12px;
}
</style>


| 工具     | 核心功能            | 语言支持       | AI 模型               | 价格     | 特色                     |
| -------- | ------------------- | -------------- | --------------------- | -------- | ------------------------ |
| Cursor   | 智能补全、代码生成  | 多语言（主要英文） | Claude 3.5、GPT-4o | $20/月   | VS Code 集成       |
| Windsurf | 深度代码理解        | 多语言（70种） | Claude 3.5、GPT-4o | $15/月   | 上下文感知、依赖分析 |
| Trae     | AI 代码生成、多模态 | 中英双语       | Claude 3.5、GPT-4o、豆包 | 免费     | 全流程支持、原生中文 |
 
适合多语言开发和需要 团队协作 的项目，尤其适合对代码质量有较高要求的开发环境， 能够显著提高代码编写的速度与准确性。

---
layout: center
---

# 一键生成简历网站

---

# 使用 Bolt.new

<v-clicks>

## 地址

一键生成网站：[Bolt.new](bolt.new)

## 提示词

```md
九旬，26 岁，清华大学计算机专业本科毕业，曾在百度实习，目前任职字节跳动算法工程师。
精通 Python、C++等编程语言，熟练掌握 TensorFlow、PyTorch 等框架，具备丰富的算法设计与优化经验。
曾参与多个项目，主导核心功能开发，优化性能，提升业务指标。
具有扎实的理论基础和较强的学习能力，善于团队协作，能高效解决问题。

请根据我上面的个人信息，帮我生成我的简历网站。
```

## 扫码查看

地址转二维码：[链图](https://qr.windliang.wang)

</v-clicks>


---
layout: center
---

<v-clicks>


# Trae介绍​

> Trae的全称是The Real AI Engineer（AI工程师），这是字节跳动推出的AI原生集成开发环境（IDE）的官方命名。 

<br>​
**定位：Trae国内版是国内首个AI原生集成开发环境工具(AI IDE)，能充分释放AI的潜力。​**

<br>

## 重点功能：​

- 多模态交互：支持语音指令、草图设计生成代码（如网页前端草图转HTML/CSS）。​
- 上下文感知：跨文件、跨模块理解项目架构，生成一致性代码。​
- 安全合规：训练数据完全来自国内开源项目，符合网络安全法要求。​


</v-clicks>


---

<style>
.slidev-layout table {
  font-size: 12px;
}
</style> 


<v-clicks>



# Trae国内版与国际版功能对照表

| 对比维度 | 国内版 | 国际版 |
|---------|-------|-------|
| **AI模型** | 字节跳动Doubao-1.5-pro、DeepSeek R1/V3（中文优化） | GPT-4o、Claude-3.7-Sonnet（全球化通用） |
| **官网地址** | trae.com.cn（中文界面，无地区限制） | trae.ai（多语言界面，需科学上网访问） |
| **登录方式** | 手机号/掘金账号登录（账户隔离） | 谷歌账号登录 |
| **网络要求** | 直连国内服务器，响应速度快 | 需科学上网，部分场景可能受限 |
| **核心功能** | 代码补全、智能问答、内置预览插件（免费） | 支持上传参考图生成代码（Claude模型）、更开放的全球化开发需求 |
| **特色功能** | 掘金社区集成、中文网页优化 | 多语言开发支持、Claude模型优先级更高 |
| **适用场景** | 中文开发环境、本地化需求 | 国际化项目、需复杂图像解析的场景 |
| **模型性能** | 中文代码处理更优，响应稳定 | 全球通用任务表现更强，但Claude-3.7需排队 |
| **下载地址** | https://www.trae.com.cn | https://www.trae.ai |


</v-clicks>


---
layout: center
---


<v-clicks>

## 使用Trae​
- 下载Trae​
- 梳理需求​
- 梳理逻辑​
- 告诉他技术栈​
- 你想要什么

  
</v-clicks>
---
layout: center
---

# 基础操作​

- 界面讲解​
- 如何使用
​
---
layout: center
---

<v-clicks>

# 核心功能解析​

  1. 智能问答Chat：依托强大的模型，让小白也能编程​
  2. 智能上下文：让AI更好的处理问题​
  3. 代码补全：智能预测代码补全，快速修改bug​
  4. 多模态：设计图一键生成代码​
  5. Builder：拆解任务并多生成多文件代码

</v-clicks>

---
layout: center
---


<v-clicks>


# 智能问答 

## 位置
- 侧边问答
- 内嵌对话

## 功能重点
- 代码问题，一问即答。
- 错误修复，智能建议。
- 需求生成，快速响应。
- 上下文关联，精准问答。
- 代码解释，一目了然。


</v-clicks>


---
layout: center
---


<v-clicks>


# Builder 模式

- 全自动代码生成，提升开发效率。
- 对话式迭代开发，省去手动操作。
- AI自动补全，简化编码流程。
- 从需求到项目，一步到位。
- 智能生成代码，减少重复工作。


</v-clicks>


---
layout: center
---

<v-clicks>



# 上下文引用
- 多级引用，智能关联。
- 文件拖拽，自动理解。
- 报错关联，快速定位。
- 项目语境，AI自动掌握。
- 代码交互，精准高效。


</v-clicks>


---
layout: center
---


<v-clicks>



# 多模态开发
- 设计图转代码，看图写程序。
- 截图标注，需求修改。
- 非技术人员，也能编程。
- 多模态输入，简化开发。
- 原型图生成代码，快捷方便。


</v-clicks>



---
layout: center
---

<v-clicks>



# 免费模型
- 内置强大AI模型，免费使用。
- 国内版模型，性能优越。
- 海外版模型，功能全面。
- AI协同编程，效率倍增。
- 高性能模型，助力开发。

</v-clicks>

---
layout: center
---


<v-clicks>



# Trae其他用法
- 介绍项目 
- 写作
- 写commit

其他用法可以参考官方文档：https://docs.trae.ai/docs


</v-clicks>


---
layout: center
---

# 对于普通人

<v-clicks>

- ### 让技术平权，编程不再是少数人的专利，而是大众可获取的能力

<!-- 打破，我只差一个程序员的口号 -->
<br>

- ### 让想法落地，开发周期大幅缩短，从想法到产品的时间被压缩
<!-- 快速验证一个MVP，快速验证，快速试错 -->

<br>

- ### 需求洞察力和创造力将成为关键


</v-clicks>


---
layout: center
---

# 联系我

<img src="https://s2.loli.net/2025/03/17/bvMlHDcVJWiNZ1w.png" style="margin: auto;;width:30%;" alt="">
 
