# SirGuanZz · 个人简历页

单页静态简历站点，面向前端开发工程师职位展示。纯 HTML / CSS / JS，无构建依赖，浏览器直接打开即可。

## 页面结构

| 区块 | 内容 |
|------|------|
| Hero | 头像、定位与一句话简介 |
| About | 个人概述与数据卡片 |
| Skills | 技术栈分类与熟练度 |
| Experience | 工作经历时间线 |
| Education | 教育背景 |
| Projects | 项目经历 |
| Strengths | 个人优势 |
| Contact | 联系方式 |

## 本地预览

```bash
# 方式一：直接打开
open personal-skills.html

# 方式二：本地静态服务（推荐，避免部分资源路径问题）
npx serve .
```

打开后访问根目录下的 `personal-skills.html`。

## 目录说明

```
.
├── personal-skills.html  # 简历主页面（样式与脚本内联）
├── avatar.png            # Hero 头像
└── README.md
```

## 技术说明

- 单文件落地，便于分享与部署到 GitHub Pages / 任意静态托管
- 含粒子背景、滚动显现、技能条动画等轻量交互
- 响应式布局，适配桌面与移动端
