---
title: "iQualityR: 工业级统计质量管理引擎"
description: "为 R 语言注入中国传统色美学，构建严谨且优雅的 SPC 与质量分析工作流。"
date: 2026-04-11
lastmod: 2026-04-11

# 视觉控制
hidemeta: true      # 隐藏日期等元数据，使其更像一个正式页面
showtoc: true       # 显示右侧目录
tocopen: true       # 默认展开目录

# 封面图 (建议放一张最惊艳的“九宫格”合成图)
cover:
    image: "project/iQualityR/images/hero-grid.png"
    alt: "iQualityR Visual Grid"
    caption: "iQualityR: 严谨统计与东方美学的交汇"
    relative: true

# 标签与分类
categories: ["Project"]
tags: ["SPC", "Quality Management", "R-Package", "Data Visualization"]
---

## 🚀 项目愿景

`iQualityR` 不仅仅是一个计算 $d_2, c_4$ 等统计常数的工具包，它致力于解决工程实践中“数据图表枯燥、信息密度低、审美缺失”的痛点。通过内置中国传统色调色盘与高度封装的 `ggplot2` 模板，让每一份质量报告都具备**科研级的严谨**与**艺术级的视觉**。

---

## ✨ 核心特性

* **Sigma Engine v2**: 支持超过 14 种概率分布的过程能力分析 ($C_p, C_{pk}, P_p, P_{pk}$)。
* **Aesthetic Presets**: 内置「青雀头黛」、「朱漆描金」等 12 套工业美学主题。
* **Ready-to-Publish**: 一键生成符合 Minitab 技术标准且可直接用于学术发表的高清图表。
* **Seamless Integration**: 完美兼容 `Tidyverse` 生态，支持管道符 `|>` 操作。

---

## 🖼️ 视觉阵法 (九宫格展示)

> *此处你可以利用 Markdown 语法排列 8 张缩略图，中心放置项目 Logo，形成你设想的视觉合力。*

| | | |
| :---: | :---: | :---: |
| ![疏影](images/p1.png) | ![叠嶂](images/p2.png) | ![流云](images/p3.png) |
| ![寒潭](images/p4.png) | **[ iQualityR ]** | ![破晓](images/p6.png) |
| ![乱石](images/p7.png) | ![远岫](images/p8.png) | ![归鸟](images/p9.png) |

---

## 📦 快速开始

```r
# 安装开发版本
# install.packages("devtools")
devtools::install_github("chenzhiming/iQualityR")

library(iQualityR)

# 开启“矿影探索”科研主题
set_iq_theme("mineral")

# 执行单值控制图分析
spc_chart(data, type = "I-MR")
```

---

## 📖 文档导航

* [安装指南](installation)
* [SPC 模块详解](spc-module)
* [中国传统色调色盘使用手册](colors)