# ABS齿数计算器 / ABS Sprocket Calculator

[English](#english) | [中文](#中文)

---

## English

### ABS Sprocket Calculator

A mobile-friendly web tool for calculating motorcycle sprocket tooth count when changing tire sizes.

**Live Demo:** https://zhangzihao0101-byte.github.io/abs-calculator/

### Features

- 📱 **Mobile Optimized** - Works perfectly on iOS Safari, Android Chrome, and desktop browsers
- 🔢 **Real-time Calculation** - Instant results as you type
- 🔄 **Bidirectional Conversion** - Calculate from front or rear sprocket
- 📊 **Visual Feedback** - Color-coded results showing increases (green) and decreases (red)
- ⚠️ **Warning System** - Alerts when chain/sprocket changes exceed 10%
- 📋 **One-click Copy** - Copy results to clipboard
- 🌐 **No Dependencies** - Pure HTML, CSS, and JavaScript

### Usage

1. Enter your original tire size (e.g., 120/70-12)
2. Enter the new tire size (e.g., 130/70-12)
3. Enter original sprocket tooth count
4. Select calculation direction (front or rear)
5. View recommended new tooth count

### Tire Size Format

Standard motorcycle tire size: `Width/AspectRatio-RimDiameter`

Example: `120/70-12`
- Width: 120mm
- Aspect Ratio: 70%
- Rim: 12 inches

### Formula

```
Tire Diameter = Rim × 25.4 + 2 × (Width × Aspect Ratio)
New Tooth Count = Original Count × (New Circumference ÷ Original Circumference)
```

---

## 中文

### ABS齿数计算器

一款适用于移动端的网页工具，用于计算摩托车改装轮胎后需要更换的齿盘齿数。

**在线访问：** https://zhangzihao0101-byte.github.io/abs-calculator/

### 功能特点

- 📱 **移动端优化** - 在iOS Safari、安卓Chrome和桌面浏览器上完美运行
- 🔢 **实时计算** - 输入即显示结果
- 🔄 **双向转换** - 可从前齿盘或后齿盘计算
- 📊 **直观显示** - 绿色表示增加，红色表示减少
- ⚠️ **警告系统** - 当变化超过10%时提醒
- 📋 **一键复制** - 复制结果到剪贴板
- 🌐 **无依赖** - 纯HTML、CSS、JavaScript，无需网络

### 使用方法

1. 输入原轮胎尺寸（如：120/70-12）
2. 输入新轮胎尺寸（如：130/70-12）
3. 输入原齿盘齿数
4. 选择计算方向（前齿盘/后齿盘）
5. 查看推荐的新齿数

### 轮胎尺寸格式

标准摩托车轮胎尺寸格式：`宽度/扁平比-轮毂直径`

例如：`120/70-12`
- 宽度：120毫米
- 扁平比：70%
- 轮毂：12英寸

### 计算公式

```
轮胎直径 = 轮毂 × 25.4 + 2 × (宽度 × 扁平比)
新齿数 = 原齿数 × (新轮胎周长 ÷ 原轮胎周长)
```

---

## 更新日志 / Changelog

### v1.0.0 (2026-04-08)
- 🎉 初始版本发布
- ✅ 实现核心计算功能
- 📱 全面iOS兼容优化
- 🌐 部署到GitHub Pages
