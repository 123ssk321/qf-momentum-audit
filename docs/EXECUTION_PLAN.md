# Momentum Audit execution plan

Prepared 2026-10-25. **Queued; implementation inactive.** Original idea #1.

## Product contract

Research two or three prespecified momentum variants, exposure and cost sensitivity, and all failures. Public factor-series results are educational; an individual-stock alpha claim requires point-in-time universe and delisting data.

## Architecture and data

Public Fama-French series for calculation checks. Public constituent approximations must be labeled survivor-biased. Licensed historical security histories are an optional later gate, not assumed. Version inputs and generated seeds. Separate ingestion/generation, domain model, evaluation and public interface. First measure a bounded local run; paid data and cloud compute are outside this plan.

## Evaluation contract

Timestamp contract, fixed hypotheses, lagged features, holdout, turnover, cost sensitivity, factor exposures and complete variant log. Prespecify baselines, data splits and failure categories before final evaluation. Record exact commands, resource measurements, all tried variants and negative results. Simulated evidence remains separate from real-market or user validation.

## Milestones and hours

Months are relative to future activation. First public functional result: month 5; final decision: by month 10. One candidate uses the shared 16-hour weekly capacity, never six concurrent commitments. Total 312 hours includes 120 reserve.

| Milestone | Relative window | Task hours | Reserve | Cumulative |
| --- | --- | ---: | ---: | ---: |
| QM-M1: Question and data audit | Months 1–2 | 32 | 20 | 52 |
| QM-M2: Signal pipeline and baselines | Months 1–2 | 32 | 20 | 104 |
| QM-M3: First public bias audit | Month 5 | 32 | 20 | 156 |
| QM-M4: Walk-forward and cost study | Months 5–7 | 32 | 20 | 208 |
| QM-M5: Exposure and robustness study | Months 6–8 | 32 | 20 | 260 |
| QM-M6: Final research case and decision | Months 7–10 | 32 | 20 | 312 |

## Public result and release gate

At milestone 3 publish a runnable artifact, generated or permitted inputs, correctness checks, a baseline, exact run instructions and an honest limitations report. This planning repository is not that artifact. A later stable release needs reproducible evaluation, failure evidence, bounded resource use and a named user workflow.

## Product decision

A research audit module may have value; a raw momentum signal is unlikely to be a distinct product. Build as a research case using Trading Lab facilities, not a new backtester. If only current constituents or unverifiable corporate actions are available, publish method validation and data-limit analysis instead of stock-level alpha claims. At each milestone decide continue, narrow or park using actual hours and evidence. No recurring monitor, spending, live trading, conference submission or implementation is activated by this plan.
