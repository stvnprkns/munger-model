# Munger Decision Models

[![skills.sh](https://skills.sh/b/stvnprkns/munger-model)](https://skills.sh/stvnprkns/munger-model)

A multidisciplinary decision framework inspired by Charlie Munger's published work. It helps agents assess investments, products, strategies and consequential decisions through causal reasoning, inversion, incentives, opportunity cost, interacting effects and explicit change-of-mind conditions.

> The goal is a better decision—not a longer list of mental models.

## Included skill

### `apply-munger-models`

Use it to:

- pressure-test an opportunity or strategy;
- compare real alternatives, including waiting;
- invert a thesis into a causal failure path;
- inspect incentives and second-order effects;
- distinguish a useful product from a durable business;
- create a decision record with falsifiable forecasts.

The skill is comprehensive but layered: it leads with the judgment, isolates the decisive uncertainty and makes the next test executable.

## Install

Install from the public GitHub repository with the Skills CLI:

```bash
npx skills add stvnprkns/munger-model
```

Install only this skill from the repository:

```bash
npx skills add stvnprkns/munger-model --skill apply-munger-models
```

The CLI is supplied by the existing `skills` npm package. This repository does not publish or require a separate npm package.

## Invoke

Examples:

```text
Use $apply-munger-models to assess whether we should build this product.
Use $apply-munger-models to invert my investment thesis.
Use $apply-munger-models to compare this acquisition with waiting.
```

The description also allows compatible agents to activate the skill implicitly when the request calls for rigorous opportunity assessment, inversion, incentives analysis or a decision journal.

## Repository structure

```text
munger-model/
├── README.md
├── LICENSE
├── CHANGELOG.md
└── skills/
    └── apply-munger-models/
        ├── SKILL.md
        └── references/
            ├── decision-journal.md
            ├── misjudgment.md
            ├── models.md
            └── opportunities.md
```

## Source and attribution

This is an independent analytical tool inspired by themes in Charlie Munger's speeches and *Poor Charlie's Almanack*. It is not affiliated with Charlie Munger's estate, Berkshire Hathaway or the book's publishers.

Primary source:

- [*Poor Charlie's Almanack* — Stripe Press](https://www.stripe.press/poor-charlies-almanack)
- [Published excerpt: *The Psychology of Human Misjudgment*](https://assets.stripeassets.com/fzn2n1nzq965/0RUnI35jpt78x10nvlO2Y/b66a46dba182182a2a0082213eafc634/SP_PCA-ZINE_2023_11_27.pdf)

Secondary projects influenced the packaging and workflow, not the historical attribution:

- [Munger Observer](https://clawbot.ai/skills/munger-observer.html)
- [Munger's Latticework Mental Models](https://mcpmarket.com/tools/skills/munger-s-latticework-mental-models)
- [AI-reconstructed Medium list supplied during development](https://medium.com/@ari.blog/i-used-ai-to-reconstruct-charlie-mungers-mental-models-here-s-the-full-list-979b8820752d)

The skill avoids impersonation, fabricated quotations and presenting reconstructed lists as Munger's official canon.

## License

MIT. See [LICENSE](LICENSE).
