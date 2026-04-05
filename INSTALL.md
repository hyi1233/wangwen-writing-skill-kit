# 📦 网文徐掌柜拆书体系 - 安装指南

> 基于 26 本拆书实录，132 张知识卡片，5 个 Skill 技能

## 快速安装

### Claude Code 本地安装
```bash
cp -r xzhang-plugin "~/.claude/plugins/xzhang-plugin"
```

### 或使用压缩包
```bash
unzip xzhang-skill-pack.zip -d ~/.claude/plugins/
```

## 安装验证
安装后在 Claude Code 中，以下场景会自动激活对应技能：
- 写开篇/黄金三章 → `网文开篇设计`
- 设计金手指/系统 → `网文金手指设计`
- 写正文/修改文笔 → `网文正文技法`
- 去除AI味 → `去AI化写作`
- 拆解某本书/做写作规划 → `网文拆书与节奏`

## 目录结构
```
xzhang-plugin/
├── .claude-plugin/plugin.json   ← 插件清单
├── skills/
│   ├── skill-01-开篇设计/SKILL.md
│   ├── skill-02-金手指设计/SKILL.md
│   ├── skill-03-正文技法/SKILL.md
│   ├── skill-04-去AI化/SKILL.md
│   └── skill-05-拆书节奏/SKILL.md
```

## 跨平台使用
将 `xzhang-plugin` 或 `xzhang-skill-pack.zip` 复制到任何使用方的 Claude Code 插件目录即可。
