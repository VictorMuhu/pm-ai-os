# Metrics Eval

> Evaluation rubric for AI-generated metric stacks or experiment designs.

## Dimensions

| Dimension | Score (1–5) | Notes |
|---|---|---|
| North star clarity | | Is the north star singular and meaningful? |
| Metric formulae | | Does every metric have a formula and data source? |
| Guardrail coverage | | Are guardrails present and meaningful? |
| Instrumentation awareness | | Are gaps in current instrumentation flagged? |
| Leading/lagging balance | | Are both leading and lagging metrics present? |
| Experiment rigor (if applicable) | | Is success criteria pre-committed? Sample size calculated? |

## Readiness rating

- **Ready**: All dimensions 4+
- **Needs revision**: Missing formulae or uninstrumented metrics without flagging = blocker

## Common failure modes

- Metrics named but not defined (no formula or source)
- No guardrail metrics
- Success criteria defined after seeing results
- Instrumentation gaps not flagged before launch
