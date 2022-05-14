# e-mall

a front end project for e-mall web

本文件夹结构：

安装 tailwindcss 带来的

- node_modules
- package.json
- package-lock.json
- tailwind.config.js

源代码文件

- src

说明文档

- README.md

## 前置条件

- 安装 node.js（用于配置本地 Tailwind CSS）

## 我的 VSCode 配置

插件

- HTML Snippets（提供 HTML 代码片段功能）
- HTML CSS Support
- HTML Preview（提供 HTML 文件效果预览）
- Tailwind CSS IntelliSense（提供 Tailwind CSS 相关的 CSS 智能提醒）
- Tailwind Docs（快速打开 Tailwind 官方文档）
- Tailwind Snippets（提供 Tailwind 代码片段）

## 小程序

小程序不适合初学（？）

## 纯混合开发

## 响应式前端设计

响应式的实现：使用栅格代替x,y坐标

表示能在多端口上能保持页面的一致性

> vue , react 和其他的前端框架
> vue 和 react 用于前端应用的设计，其他的用于 UI 制作

### CSS

三种类型：

- 内联样式
- 全局样式

### tailwindcss

功能优先编译型的语义化原子样式库

原子化：

1. 第一阶段，原生写法
2. 第二阶段，css 组件化(外观和功能结合)
3. 第三阶段，css 零件化

```html
<!-- 内联 -->
<div style="borderRadius:'0.5rem', padding:'1rem'">click</div> 
<!-- 使用css样式button -->
<div class="button">click</div>


<button>click</button>

<div class="rounded-lg p-4">Click</div>
```

[Installation: Tailwind CLI - Tailwind CSS](https://tailwindcss.com/docs/installation)

安装方式：CLI, Postcss, framework Guide, Play CDN

推荐 CLI 方式安装

#### CLI方式安装

prerequirements: node.js

[Installation: Tailwind CLI - Tailwind CSS](https://tailwindcss.com/docs/installation)

大小属性的单位：绝对单位px（可能在不同的分辨率的终端上显示不一致）

相对单位：rem（相对）
