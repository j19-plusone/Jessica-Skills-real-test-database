# Umami
- Repo: https://github.com/umami-software/umami · ⭐ 39.8k（2026-11-01）· License: MIT
- 功能 / What: 轻量隐私网站统计 / privacy-friendly web analytics
- 状态 / Status: **测试中 · Day 7 (2026-11-08) / Testing · Day 7**

## 测试检查点 / Test checkpoints（仅客观数据 / objective data only）
| Day | 日期 Date | 部署状态 Deploy | 关键指标 Metrics | 成本 Cost | 故障 Incidents |
|---|---|---|---|---|---|
| D7 | 2026-11-08 | 未部署 / not deployed（需 Docker 或 PostgreSQL；PostgreSQL :5432 无响应，无 Docker） | 已检查的公开站点首页无 Umami 脚本；pageviews：0 | $0 | 无 / none |
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
- 过程与结果 / Process & result: 本机无 Docker/PostgreSQL，未部署；`npm view @umami/node` 确认 SDK 可安装（0.4.0）
- 评分 / Scores: 效果 8 · 价值 9 · 易用 8 · 成本 9 → **总分 8.5**
- 初筛结论 / Screening verdict: **保留（初筛，Jessica 2026-11-01 确认）** — MIT、最轻，适合所有站点统一统计
