# 许居衍院士写作风格 Skill

模仿中国工程院院士许居衍半导体产业分析写作风格的 Claude Code Skill。

## 安装

```bash
mkdir -p ~/.claude/skills/xu-juyan-style
curl -o ~/.claude/skills/xu-juyan-style/SKILL.md \
  https://raw.githubusercontent.com/MouYou1566/Juyan_Xu_writing_styke_skill/main/.claude/skills/xu-juyan-style/SKILL.md
```

安装后重启终端，在 `/skills` 中即可看到 `xu-juyan-style`。

## 使用

在 Claude Code 中直接：

```
/xu-juyan-style 写一段关于领域专用化的分析文字
```

或在对话中说"用 xu-juyan-style 写……"。

## 功能

- 模仿许居衍院士的辩证思维框架（通用vs专用、简vs繁、技术vs架构）
- 使用其概念体系（硅-冯范式、半导体循环律、统一芯片范式等）
- 遵循其三层次论述结构（技术层→产业层→范式层）
- 包含真实原文例句和语料

## 语料来源

- 许居衍院士公开论文和演讲全文
- 核心概念：半导体特征循环、硅-冯范式、后摩尔时代四类范式
- 时间跨度：2008—2023 年

## 授权

MIT
