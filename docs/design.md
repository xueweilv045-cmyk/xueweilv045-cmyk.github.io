---
layout: default
---

# 设计说明 (Design) — 个人网站

## 页面区块与浏览顺序
| 顺序 | 区块 | 内容 |
|------|------|------|
| 1 | Hero | 姓名「吕雪薇」+ 定位「正在学 AI 开发的信管学生」 |
| 2 | About | 个人简介（专业背景、学习方向） |
| 3 | Projects | 课程作品或自学项目（占位，后续补充） |
| 4 | Skills | C++、AI 学习方向 |
| 5 | Contact | QQ 邮箱：3495821294@qq.com |

## 颜色与字体
- 主色：使用模版默认配色（蓝灰基调）
- 字体：模版默认字体（系统无衬线字体）
- 深色模式：关闭（`darkmode: false`）

## 响应式要求
- 桌面端：内容完整展示，无横向滚动
- 手机端：文字可读，按钮可点，布局自适应

## 文件映射
个人网站项目/
├─ _config.yml          → 核心配置（个人信息、项目、经历）
├─ index.md             → 首页入口
├─ assets/main.scss     → 样式入口
├─ assets/js/index.js   → JavaScript 交互
├─ assets/favicon.ico   → 网站图标
├─ images/              → 个人头像与素材
├─ docs/
│  ├─ prd.md            → 产品需求文档
│  ├─ design.md         → 设计说明（本文档）
│  └─ checklist.md      → 验收清单
├─ report/final-report.md → 最终报告
├─ screenshots/         → 证据截图
└─ README.md            → 仓库说明与 Pages 链接

## 模板保留与修改
- 保留：整体布局、样式框架、响应式机制
- 修改：`_config.yml` 中的个人信息、社交链接、项目内容
- 不修改：`_layouts/`、`_sass/` 层（除非样式冲突）

## 图片素材来源
- 个人头像：由用户本人提供
- 其他图片：使用模版自带的授权图片，或替换为本人素材

## 隐私说明
- 仅公开 QQ 邮箱作为联系方式
- 不公开手机号、住址、身份证件、课程邀请码
- 不提交 API Key、密码或 Token 到仓库
- 仓库为 Public，但排除敏感信息
