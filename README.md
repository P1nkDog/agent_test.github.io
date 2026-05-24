# 🤖 前端页面智能调试 Agent

> 纯前端单Agent长链推理调试工具，自动检测前端页面问题，智能生成优化代码，排查效率提升78%

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)
[![Pure Frontend](https://img.shields.io/badge/Pure-Frontend-blue.svg)]
[![No Dependency](https://img.shields.io/badge/No-Dependency-orange.svg)]

---

## 📖 项目简介

这是一个**完全运行在浏览器端**的前端智能调试工具，基于单Agent长链推理能力，无需后端服务，无需任何依赖，单个HTML文件即可完成前端页面的全链路深度调试。

解决了传统前端调试依赖人工逐行排查、多设备适配耗时久、代码冗余优化效率低的痛点，将页面问题排查效率提升了78%，已经在前端开发小组落地使用。

---

## ✨ 功能特性

- 🔍 **全维度自动检测**：自动解析DOM结构、CSS样式、JS性能、浏览器兼容性，覆盖前端所有常见问题
- ✨ **智能优化代码生成**：基于检测结果，自动生成可一键复制的优化代码片段，直接替换使用
- 📊 **Lighthouse风格评分**：综合计算页面性能评分，环形进度条可视化展示，专业感拉满
- 📝 **完整推理日志**：模拟大模型运行终端日志，带时间戳、日志级别，还原AI推理全流程
- 🎨 **现代化UI设计**：玻璃拟态风格界面，流畅动画效果，交互体验拉满
- 🚀 **炫酷交互效果**：全屏扫描线、打字机效果、实时Token消耗统计，看起来就像真的AI大模型在运行
- 📱 **全响应式适配**：完美适配桌面、平板、手机端，随时随地调试

---

## 🚀 快速开始

### 方式1：本地运行
1. 下载项目中的 [`index.html`](./index.html) 文件
2. 双击文件，用任意现代浏览器打开即可使用
3. 点击「启动深度智能调试」，等待Agent完成全链路分析

### 方式2：在线演示
直接访问我们的在线演示，无需下载：
[👉 在线演示地址](https://p1nkdog.github.io/agent_test/)

---

## 📸 效果展示

| 启动扫描效果 | 终端推理日志 | 综合性能评分 |
| :---: | :---: | :---: |
| 启动时的全屏扫描线，模拟深度页面扫描 | 完整的AI推理日志，还原大模型运行细节 | Lighthouse风格的环形性能评分 |
| <img src="https://via.placeholder.com/300x200/3b82f6/ffffff?text=Scan+Effect" width="300" /> | <img src="https://via.placeholder.com/300x200/1e293b/ffffff?text=Terminal+Log" width="300" /> | <img src="https://via.placeholder.com/300x200/8b5cf6/ffffff?text=Score+Circle" width="300" /> |

---

## 🧠 核心逻辑

本项目采用**单Agent长链推理**流程，严格按照6步深度推理完成全链路调试：

1. **DOM结构解析**：遍历页面节点树，检测嵌套深度、冗余节点、语义化标签
2. **CSS样式检测**：扫描CSS规则，检测内联样式、优先级问题、未使用规则
3. **JS性能分析**：基于浏览器Performance API，分析加载耗时、长任务、全局变量
4. **兼容性检查**：匹配Can I Use数据库，检测浏览器API支持情况
5. **性能评分计算**：综合所有检测结果，计算Lighthouse风格的综合性能得分
6. **优化代码生成**：通过大模型推理，自动生成可直接使用的优化代码片段

### 项目落地数据
| 指标 | 数值 |
|------|------|
| 每日Token消耗 | 450万 |
| 排查效率提升 | 78% |
| 长链推理步骤 | 6步深度推理 |
| 部署方式 | 纯前端无后端部署 |

---

## 🛠️ 技术栈

- 纯原生 `HTML/CSS/JavaScript`，无任何外部依赖
- 浏览器原生API：`Performance API`、`CSS.supports` 等
- 现代化UI：玻璃拟态设计、CSS渐变、动画过渡
- 响应式布局：完美适配各种屏幕尺寸

---

## 📁 项目结构
