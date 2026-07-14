# SirGuanZz · 个人简历页

单页静态简历站点，面向前端开发工程师职位展示。纯 HTML / CSS / JS，无构建依赖。

**在线访问：** https://sirguanzz.github.io/Resume/

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
open index.html

# 方式二：本地静态服务（推荐）
npx serve .
```

## 目录说明

```
.
├── index.html   # 简历主页面（样式与脚本内联）
├── avatar.png   # Hero 头像
└── README.md
```

## GitHub Pages

站点由仓库 `main` 分支根目录部署。推送更新后，约 1～2 分钟可在上述地址访问。

## 技术说明

- 单文件落地，便于分享与静态托管
- 含粒子背景、滚动显现、技能条动画等轻量交互
- 响应式布局，适配桌面与移动端
