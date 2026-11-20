# Market to Product

帮助产品经理调研自己所在行业的市场环境、市面产品和重点竞品。接到任务后，围绕我方要做的产品决定快速搭建分析框架、查证关键问题，形成可用于团队评审的结构化报告。

报告依次覆盖研究目的、市场环境、市面产品与细分机会、重点竞品公司与产品、我方产品决策。用 SWOT 对照我方能力与外部机会，给出方案取舍、优先级和验证条件。

## 在 Codex 中使用

下载或克隆此仓库，将整个 `market-to-product/` 文件夹复制到个人 Skills 目录。个人目录使用 `~/.agents/skills`。见 [OpenAI 官方安装说明](https://learn.chatgpt.com/docs/build-skills)。

```sh
git clone https://github.com/17863934068-droid/market-to-product.git
mkdir -p "$HOME/.agents/skills"
cp -R market-to-product/market-to-product "$HOME/.agents/skills/"
```

开一个新会话，用 `$market-to-product` 调用。可以直接提供研究问题、地区、重点竞品和我方已知条件，也可以附上已有材料，要求给出分析框架或直接开展调研。

> $market-to-product 我们已有面向小型连锁门店的排班产品，正在考虑先做自动排班、换班审批还是工时统计。请研究目标客群、现有替代和一家重点竞品的公司与产品现状，输出五章报告，给出我方功能优先级、首版范围、SWOT 和验证计划。

可直接查看[方法说明](market-to-product/SKILL.md)、[报告模板](market-to-product/references/report-template.md)和[证据校验规则](market-to-product/references/evidence-checks.md)。
