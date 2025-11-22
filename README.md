# 宸的空间站 · 静态原型（HTML + Tailwind）

这是一个可直接本地预览的静态站点原型，用于对齐信息架构与UI风格。

## 目录
- index.html          首页
- resume.html         简历（内嵌 PDF 预览 & 下载）
- projects.html       项目经历（卡片网格 + 详情）
- product.html        产品经历（卡片网格 + 详情）
- blog.html           有趣的思考（文章列表 + 详情）
- travel.html         出行轨迹（地图占位 + 时间轴）
- hobbies.html        兴趣爱好（卡片）
- connect.html        互动区（联系表单 + 留言板）

## 使用方法
1. 下载并解压本项目。
2. 双击打开 `index.html` 即可本地预览。
3. 将你的 `resume.pdf` 放入 `assets/` 目录覆盖占位文件。
4. 在 `projects.html` / `product.html` 里复制卡片作为模版，替换为实际内容。

## 进阶（后续可做）
- 将静态页迁移到 Next.js（保持相同信息架构）。
- 接入 Mapbox / Leaflet 渲染出行地图。
- 将留言板/联系表单接后端（Node.js + MongoDB）或表单服务（Formspree / Netlify Forms）。
- 博客接入 Markdown 目录并做静态生成（如 Next.js MDX）。

> 视觉风格：深色星空 + 霓虹紫青，卡片玻璃拟态，轻动效。
