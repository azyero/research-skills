[中文版](../README.md) | English

# Research Agent Skills Pack

Universal AI Agent skills collection for researchers, covering 10 academic disciplines.

## Features

**Universal Compatibility** — Works with Hermes, Claude Code, Cursor, Codex, Windsurf and other mainstream AI Agents. Switch tools without switching skills.

**Wide Discipline Coverage** — 10 directions: General, Computer Science, Biomedical, Social Science, Economics/Finance, Materials/Chemistry, Environmental Science, Humanities, Law, Education/Psychology.

**Bilingual** — Every skill available in both Chinese and English.

**Structured Output** — Consistent templates for literature reviews, research designs, experiment plans, and paper drafts. Output ready for proposals and papers.

**Quality Control** — Global rules: no fabrication, mark uncertainty, separate facts from inferences, proactively identify research design flaws.

**One-Command Install** — Send the repo URL to your Agent and it installs automatically.

## Who It's For

- Graduate students: proposals, literature reviews, paper writing
- Researchers: experiment design, data analysis, paper reproduction
- Interdisciplinary research: methodology support across fields

## Skills List

| Skill | Discipline | Purpose |
|-------|------------|---------|
| [literature-review](skills/general/) | General | Literature review, research map building |
| [cs-paper-reproduction](skills/computer-science/) | Computer Science | Paper reproduction, method analysis |
| [biomedical-evidence](skills/biomedical/) | Biomedical | Mechanism analysis, evidence hierarchy |
| [social-science-research-design](skills/social-science/) | Social Science | Theory framework, variable design |
| [economics-empirical](skills/economics/) | Economics/Finance | Econometrics, causal identification |
| [materials-chemistry-experiment](skills/materials-chemistry/) | Materials/Chemistry | Synthesis, characterization design |
| [environmental-science-analysis](skills/environmental-science/) | Environmental Science | Monitoring, spatial analysis |
| [humanities-textual-analysis](skills/humanities/) | Humanities | Close reading, source analysis |
| [legal-research](skills/law/) | Law | Normative analysis, case retrieval |
| [education-psychology-method](skills/education-psychology/) | Education/Psychology | Scale design, statistical analysis |

## Usage

**Easiest way: send the repo URL to your AI Agent and let it install.**

```
Please install these research skills: https://github.com/azyero/research-skills
```

The agent will automatically clone the repo and install skills to the correct location.

### Manual Installation

```bash
git clone https://github.com/azyero/research-skills.git

# Chinese version
cp -r research-skills/skills/* ~/.hermes/skills/

# English version
cp -r research-skills/en/skills/* ~/.hermes/skills/
```

### Compatible Agents

| Agent | Skills Directory |
|-------|------------------|
| Hermes | `~/.hermes/skills/` |
| Claude Code | Project root `CLAUDE.md` or `.claude/` |
| Cursor | Project root `.cursorrules` |
| Codex | Project root `AGENTS.md` |
| Windsurf | Project root `.windsurfrules` |

## Global Rules

All skills share [RESEARCH_RULES.md](skills/RESEARCH_RULES.md):

- No fabrication of literature or data
- Mark uncertainty
- Distinguish facts, inferences, and suggestions
- Proactively identify research design flaws

## License

MIT
