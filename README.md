# Frontend Dev Guide — 前端高级开发工程师方案产出指南

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Version](https://img.shields.io/badge/version-1.0.0-green.svg)](SKILL.md)

一个面向 AI 编程助手的 **前端开发工程师 Skill**，将前端工程方法论转化为可执行工作流。自动识别 5 类场景（0→1 新前端项目 / 功能开发 / Bug修复 / 技术升级 / 预研），按对应清单产出架构设计、组件方案、性能方案、测试策略等完整技术文档。

## 适用场景

| 场景 | 示例 | 产出量 |
|------|------|:---:|
| 0→1 新前端项目 | 全新 React/Vue 项目搭建 | 10-12类 |
| 中大型功能开发 | CRM 新增智能外呼前端模块 | 6-8类 |
| 小优化/Bug修复 | 列表渲染性能优化 | 2-3类 |
| 大版本技术升级 | Vue2→Vue3 迁移 | 8-10类 |
| 技术预研/选型 | 新框架评估 PoC | 3-4类 |

## 触发热词

前端开发、前端架构、前端项目、组件设计、状态管理、性能优化、框架升级、前端技术选型、Web开发、H5开发

---

## 安装

本 Skill 遵循 **Open Agent Skills 标准**（SKILL.md 格式），兼容以下工具：

### WorkBuddy / CodeBuddy

**方式一：克隆到 skills 目录**
```bash
git clone https://github.com/genapohub/frontend-dev-guide.git ~/.workbuddy/skills/frontend-dev-guide
```

### Trae

**ZIP 导入**
```bash
# 先下载并打包
git clone https://github.com/genapohub/frontend-dev-guide.git
zip -r frontend-dev-guide.zip frontend-dev-guide/
```
然后在 Trae → **设置** → **Rules & Skills** → **创建** → 上传 `frontend-dev-guide.zip`。

### Codex

```bash
# 克隆到 skills 目录
git clone https://github.com/genapohub/frontend-dev-guide.git ~/.codex/skills/frontend-dev-guide

# 或使用 cc switch (推荐)
git clone https://github.com/genapohub/frontend-dev-guide.git ~/.cc-switch/skills/frontend-dev-guide
```

重启 CC Switch客户端/Codex客户端 后自动发现。也可以在对话中输入 `$frontend-dev-guide` 手动调用。

### Cursor
```bash
# 克隆到 skills 目录
git clone https://github.com/genapohub/frontend-dev-guide.git ~/.cursor/skills-cursor/frontend-dev-guide
```

重启 Cursor客户端 后自动发现。也可以在对话中输入 `$frontend-dev-guide` 手动调用。

---

## 使用

```
帮我搭建一个新 React 项目的技术架构
用户中心模块的前端方案怎么设计
这个列表页渲染卡顿怎么优化
从 Webpack 迁移到 Vite，出个迁移方案
```

---

## 目录结构

```
frontend-dev-guide/
├── SKILL.md                  # 主指令
├── README.md
├── LICENSE
├── .gitignore
└── references/
    └── 前端开发方法论.md       # 详细方法论
```

## 许可

[MIT](LICENSE) © zhangmengbo
