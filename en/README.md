[中文版](../README.md) | English

# Research Agent Skills Pack

Universal AI Agent skills collection for researchers, covering 10 academic disciplines.

## Why This?

**The problem with other repos:**
- `everything-claude-code` — locked to Claude Code, useless if you switch agents
- `academic-research-skills` — English only, narrow discipline coverage
- Most skills repos — teach "how to use an agent", not "how to do research"

**This repo's advantages:**

| Comparison | Other Repos | This Repo |
|------------|-------------|-----------|
| Agent Support | Claude Code only | Hermes, Claude Code, Cursor, Codex, Windsurf — universal |
| Language | English | Bilingual (Chinese + English) |
| Discipline Coverage | General/CS focused | 10 disciplines (STEM, Social Science, Humanities, Law) |
| Output Format | Free-form | Structured templates (ready for proposals, papers, experiments) |
| Quality Control | None | Global rules (no fabrication, mark uncertainty, separate facts from inferences) |

**Who it's for:**
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
