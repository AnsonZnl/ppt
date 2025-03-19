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

# AI 编程入门篇

<div class="text-xl mt-4 opacity-80">
无代码基础人群如何上手 AI 编程
</div>

---
layout: center
---

# Trae介绍​

> Trae的全称是The Real AI Engineer（AI工程师），这是字节跳动推出的AI原生集成开发环境（IDE）的官方命名。 

<br>​
**定位：Trae国内版是国内首个AI原生集成开发环境工具(AI IDE)，能充分释放AI的潜力。​**

<br>
## 重点功能：​
- 多模态交互：支持语音指令、草图设计生成代码（如网页前端草图转HTML/CSS）。​
- 上下文感知：跨文件、跨模块理解项目架构，生成一致性代码。​
- 安全合规：训练数据完全来自国内开源项目，符合网络安全法要求。​


---

<style>
.slidev-layout table {
  font-size: 12px;
}
</style> 

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

---

## 什么是编程​
> 编程就是编写程序的过程，是将人类思维和指令转化为计算机可以理解和执行的语言

- 编程语言：汇编→高级语言→自然语言​

- 机器听不懂人话，所以需要和机器沟通，就需要编程语言，比如java、Python..​

- 有了AI之后，让AI充当翻译，帮我去和机器沟通​

## 编程就是把一个具体的动作抽象出来​
写一个爬虫的逻辑​
1. 引入请求库​
2. 获取数据​
3. 处理数据​
4. 保存数据​

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

集成开发环境（Integrated Development Environment ）简称IDE，类似我们写ppt，需要使用WPS一样，文件的后缀名同理。
 

---

## 使用Trae​
- 下载Trae​
- 梳理需求​
- 梳理逻辑​
- 告诉他技术栈​
- 你想要什么

---

# 基础操作​
界面讲解​
如何使用
​
---

# 核心功能解析​
  1. 智能问答Chat：依托强大的模型，让小白也能编程​
  2. 智能上下文：让AI更好的处理问题​
  3. 代码补全：智能预测代码补全，快速修改bug​
  4. 多模态：设计图一键生成代码​
  5. Builder：拆解任务并多生成多文件代码

---

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

---

# Builder 模式
- 全自动代码生成，提升开发效率。
- 对话式迭代开发，省去手动操作。
- AI自动补全，简化编码流程。
- 从需求到项目，一步到位。
- 智能生成代码，减少重复工作。

---

# 上下文引用
- 多级引用，智能关联。
- 文件拖拽，自动理解。
- 报错关联，快速定位。
- 项目语境，AI自动掌握。
- 代码交互，精准高效。

---

# 多模态开发
- 设计图转代码，看图写程序。
- 截图标注，需求修改。
- 非技术人员，也能编程。
- 多模态输入，简化开发。
- 原型图生成代码，快捷方便。

---

# 免费模型
- 内置强大AI模型，免费使用。
- 国内版模型，性能优越。
- 海外版模型，功能全面。
- AI协同编程，效率倍增。
- 高性能模型，助力开发。

---

# Trae其他用法
- 介绍项目 
- 写作
- 写commit

其他用法可以参考官方文档：https://docs.trae.ai/docs

---
