# Atrom - 现代 Astro 主题

[English](./README.md) | [中文](./README-zh.md)

一个美观、响应式的 Astro 主题，采用简洁设计和现代美学风格，专为 Astro v6 构建。支持中英文语言切换，可在导航栏中轻松切换语言版本。

## 特性

- 🎨 **简洁设计**：简约优雅的 UI 设计
- 🌍 **多语言支持**：内置中文和英文语言支持
- 📱 **响应式**：在所有屏幕尺寸上完美运行
- 🚀 **快速性能**：使用 Astro 构建，实现最佳速度
- 🎯 **现代美学**：采用 Inter 字体家族和流畅的过渡效果
- ✅ **Astro v6 兼容**：与最新版 Astro 完全兼容

## 页面

- **首页**：包含品牌介绍的 Hero 区域
- **产品**：展示产品特性
- **价值**：突出业务价值主张
- **故事**：客户评价和成功案例

## 要求

- **Node.js**：>= 22.12.0（Astro v6 要求）
- **包管理器**：推荐使用 pnpm

## 快速开始

```bash
# 安装依赖
pnpm install

# 启动开发服务器
pnpm dev

# 构建生产版本
pnpm build
```

## 项目结构

```
atrom/
├── src/
│   └── pages/
│       ├── index.astro          # 中文首页
│       ├── product.astro        # 中文产品页
│       ├── value.astro          # 中文价值页
│       ├── stories.astro        # 中文故事页
│       └── en/
│           ├── index.astro      # 英文首页
│           ├── product.astro    # 英文产品页
│           ├── value.astro      # 英文价值页
│           └── stories.astro    # 英文故事页
├── astro.config.mjs
├── package.json
└── README.md
```

## 技术栈

- **Astro**：静态站点生成器
- **CSS**：使用现代 CSS 特性的自定义样式
- **JavaScript**：交互式组件

## 语言切换

该主题支持中文和英文两种语言。语言选择器位于导航栏中，紧挨着 logo。

## 许可证

MIT
