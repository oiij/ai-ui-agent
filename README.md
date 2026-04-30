# AI UI Agent

一个基于大模型的 UI 设计生成 Agent，支持从自然语言生成 UI 设计方案及前端代码。

## 🚀 功能
- 输入描述自动生成 UI 设计
- 输出配色 / 布局 / 文案结构
- 自动生成 HTML / CSS 代码
- 支持 UI → Code 转换

## 🧠 Agent 架构

系统采用多 Agent 协作：

1. 需求理解 Agent（解析用户输入）
2. 设计生成 Agent（生成 UI 结构与风格）
3. 代码生成 Agent（输出前端代码）

## 📸 示例

输入：
> 美容行业首页 Banner，粉色系，可爱风

输出：
- UI设计方案
- 前端代码

## 🛠 技术实现

- LLM（Prompt Chain）
- 多 Agent 拆解
- 设计规范约束（Design System）
- 基础 RAG（设计参考）

## 📦 使用方式

直接通过自然语言描述 UI 需求，即可生成设计和代码。

## 📍 Demo

见下方截图 👇
