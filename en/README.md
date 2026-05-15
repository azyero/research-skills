# Research Agent Skills Pack (English)

[Hermes Agent](https://github.com/nousresearch/hermes-agent) skills collection for researchers, covering 10 academic disciplines.

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

## Installation

```bash
# Clone repo
git clone https://github.com/azyero/hermes-research-skills.git

# Copy to Hermes skills directory
cp -r hermes-research-skills/en/skills/* ~/.hermes/skills/
```

Or install individually:

```bash
cp -r hermes-research-skills/en/skills/general ~/.hermes/skills/
```

## Usage

After installation, restart Hermes. Research tasks will automatically trigger corresponding skills.

Examples:
- "Help me review the current research on LLMs in education"
- "How do I reproduce this paper's method?"
- "Design a study on social media's impact on adolescent mental health"

## Global Rules

All skills share [RESEARCH_RULES.md](skills/RESEARCH_RULES.md):

- No fabrication of literature or data
- Mark uncertainty
- Distinguish facts, inferences, and suggestions
- Proactively identify research design flaws

## Future Extensions

- NLP paper deep reading
- Clinical trial design
- DID policy evaluation
- XRD spectrum analysis
- Interview coding
- Proposal generation
- Peer review response
- Paper polishing

## License

MIT
