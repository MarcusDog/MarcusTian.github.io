# Boki的个人博客

这是一个数字未来主义风格的个人博客项目，采用 HTML、CSS（含 Tailwind CSS）、JavaScript 构建，支持文章创作、展示、编辑和粒子特效等功能。

## 项目特色

- 玻璃拟态（Glassmorphism）UI
- 粒子背景动画（基于 particles.js）
- 响应式设计，移动端友好
- Markdown 文章编辑器（EasyMDE）
- 本地存储文章与草稿
- 分类筛选与搜索
- 技能展示、项目展示、联系方式等模块

## 目录结构

```
boki/
├── articles.html         # 文章列表页
├── editor.html           # 文章编辑页
├── index.html            # 首页
├── assets/
│   └── fonts/            # 字体资源
├── css/
│   ├── animations.css    # 动画样式
│   └── style.css         # 全局样式
├── js/
│   ├── articles.js       # 文章列表逻辑
│   ├── editor.js         # 编辑器逻辑
│   ├── main.js           # 通用交互逻辑
│   └── particles-config.js # 粒子背景配置与初始化
```

## 快速开始

1. 克隆仓库到本地
2. 使用本地服务器（如 VSCode Live Server、http-server）打开 `index.html`
3. 访问首页、文章列表页和编辑页体验全部功能

## 主要功能说明

- **首页**：展示个人信息、技能、项目、最新文章、联系方式
- **文章列表页**：支持分类筛选、关键词搜索、分页
- **文章编辑页**：支持 Markdown 编辑、标签管理、图标选择、草稿保存与发布（数据存储于浏览器 localStorage）

## 依赖说明

- [Tailwind CSS](https://tailwindcss.com/)
- [Font Awesome](https://fontawesome.com/)
- [particles.js](https://vincentgarreau.com/particles.js/)
- [EasyMDE](https://github.com/Ionaru/easy-markdown-editor)（仅编辑页）

所有依赖均通过 CDN 引入，无需额外安装。

## 自定义与扩展

- 样式可在 `css/style.css` 和 `css/animations.css` 中调整
- 粒子背景配置在 [`js/particles-config.js`](js/particles-config.js)
- 文章数据结构与交互逻辑可在 [`js/editor.js`](js/editor.js) 和 [`js/articles.js`](js/articles.js) 中扩展

## 许可

本项目仅供学习和个人展示用途，版权归 Boki 所有。

---

欢迎提出建议或