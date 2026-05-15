[English Version](en/README.md) | 中文版

# 科研 Agent Skills 包

面向科研人员的通用 AI Agent 技能集合，覆盖 10 个学科方向。适用于 Hermes、Claude Code、Codex、Cursor 等主流 AI 编程/研究助手。

## Skills 列表

| Skill | 学科 | 用途 |
|-------|------|------|
| [literature-review](skills/general/) | 通用 | 文献综述、研究图谱构建 |
| [cs-paper-reproduction](skills/computer-science/) | 计算机科学 | 论文复现、方法分析、代码实现 |
| [biomedical-evidence](skills/biomedical/) | 生物医学 | 机制分析、证据等级评估、实验设计 |
| [social-science-research-design](skills/social-science/) | 社会科学 | 理论框架、变量设计、假设提出 |
| [economics-empirical](skills/economics/) | 经济金融 | 计量模型、因果识别、政策评估 |
| [materials-chemistry-experiment](skills/materials-chemistry/) | 材料化学 | 合成方案、表征设计、变量控制 |
| [environmental-science-analysis](skills/environmental-science/) | 环境科学 | 监测设计、空间分析、政策评估 |
| [humanities-textual-analysis](skills/humanities/) | 人文学科 | 文本细读、史料分析、论证设计 |
| [legal-research](skills/law/) | 法学 | 规范分析、案例检索、争议梳理 |
| [education-psychology-method](skills/education-psychology/) | 教育心理 | 量表设计、实验设计、统计分析 |

## 使用方式

**最简单的方式：把仓库地址发给你的 AI Agent，让它自己安装。**

```
请帮我安装这些科研skills：https://github.com/azyero/research-skills
```

Agent 会自动克隆仓库并将 skills 安装到正确位置。

### 手动安装

```bash
git clone https://github.com/azyero/research-skills.git

# 中文版
cp -r research-skills/skills/* ~/.hermes/skills/

# 英文版
cp -r research-skills/en/skills/* ~/.hermes/skills/
```

### 适用 Agent

| Agent | Skills 目录 |
|-------|-------------|
| Hermes | `~/.hermes/skills/` |
| Claude Code | 项目根目录的 `CLAUDE.md` 或 `.claude/` |
| Cursor | 项目根目录的 `.cursorrules` |
| Codex | 项目根目录的 `AGENTS.md` |

## 全局规则

所有 skill 共享 [RESEARCH_RULES.md](skills/RESEARCH_RULES.md) 中的通用科研守则：

- 不编造文献和数据
- 标注不确定性
- 区分事实、推断和建议
- 主动指出研究设计漏洞

## License

MIT
