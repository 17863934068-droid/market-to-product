# Market Research Skill

一套跨行业的市场调研与竞品分析方法。输入一个业务问题、市场或重点竞品，得到一份能支持产品规划、选细分市场和判断是否试点的结构化报告。

报告依次覆盖研究目的、市场大盘、产品与细分市场、重点竞品、SWOT 与决策建议。关键判断附证据和验证条件。

## 在 Codex 中使用

下载或克隆此仓库，将整个 `market-research/` 文件夹复制到个人 Skills 目录。个人目录使用 `~/.agents/skills`。见 [OpenAI 官方安装说明](https://learn.chatgpt.com/docs/build-skills)。

```sh
git clone https://github.com/17863934068-droid/market-research-skill.git
mkdir -p "$HOME/.agents/skills"
cp -R market-research-skill/market-research "$HOME/.agents/skills/"
```

开一个新会话，用 `$market-research` 调用。可以直接提供研究问题、地区、重点竞品和我方已知条件，也可以附上已有报告，让 Skill 核查证据或补写决策章节。

> $market-research 以一家德国工业视觉软件厂商为核心竞品，判断一家已有制造业客户渠道的软件公司应优先验证哪个质检场景。重点分析竞品定价、销售与交付，输出含证据来源、SWOT 和试点门槛的 Markdown 报告。

可直接查看[方法说明](market-research/SKILL.md)、[报告模板](market-research/references/report-template.md)和[证据校验规则](market-research/references/evidence-checks.md)。
