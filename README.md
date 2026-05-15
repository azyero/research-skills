# 科研 Agent Skills 包

面向科研人员的 [Hermes Agent](https://github.com/nousresearch/hermes-agent) 技能集合，覆盖 10 个学科方向。

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

## 安装

```bash
# 克隆仓库
git clone https://github.com/azyero/hermes-research-skills.git

# 复制到 Hermes skills 目录
cp -r hermes-research-skills/skills/* ~/.hermes/skills/
```

或单独安装：

```bash
cp -r hermes-research-skills/skills/general ~/.hermes/skills/
```

## 使用

安装后重启 Hermes，对话中涉及科研任务时会自动触发对应 skill。

示例：
- "帮我梳理一下大语言模型在教育领域的研究现状"
- "这篇论文的方法怎么复现"
- "帮我设计一个研究社交媒体对青少年心理健康影响的方案"

## 全局规则

所有 skill 共享 [RESEARCH_RULES.md](skills/RESEARCH_RULES.md) 中的通用科研守则：

- 不编造文献和数据
- 标注不确定性
- 区分事实、推断和建议
- 主动指出研究设计漏洞

## 扩展方向

后续可扩展的细粒度 skill：

- NLP 论文精读
- 临床试验设计
- DID 政策评估
- XRD 图谱分析
- 访谈编码
- 开题报告生成
- 审稿意见回复
- 论文润色

## License

MIT
