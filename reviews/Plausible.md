# Plausible
- Repo: https://github.com/plausible/analytics · ⭐ 29.7k（2026-11-01）· License: AGPL-3.0
- 功能 / What: GDPR 合规统计
- 状态 / Status: **测试中 · Day 7 (2026-11-08) / Testing · Day 7**

## 测试检查点 / Test checkpoints（仅客观数据 / objective data only）
| Day | 日期 Date | 部署状态 Deploy | 关键指标 Metrics | 成本 Cost | 故障 Incidents |
|---|---|---|---|---|---|
| D7 | 2026-11-08 | 未部署 / not deployed（需 Docker+ClickHouse；本机无 Docker） | 已检查的公开站点首页无 Plausible 脚本；pageviews：0 | $0 | 无 / none |
| D14 | | | | | |
| D21 | | | | | |
| D28 | | | | | |
| D35 | | | | | |
| D42 | | | | | |

> 测试期间不写意见；最终评分与结论在测试结束后填写。 No opinions during testing; final scores and verdict after the test ends.

## 最终评分 / Final verdict
_待测试结束 / After test ends_

## 初步筛选（非最终评分）/ Initial screening (not final)
- 测试级别 / Test level: **仅评审**
- 过程与结果 / Process & result: 需 Docker+ClickHouse，未部署；`npm view plausible-tracker` 可用
- 评分 / Scores: 效果 8 · 价值 7 · 易用 6 · 成本 7 → **总分 7.0**
- 初筛结论 / Screening verdict: **删除（初筛，Jessica 2026-11-01 确认）** — 与 Umami 功能重叠，择一即可
