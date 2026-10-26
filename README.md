# Vinícius Biazon

Data analyst with 10 years of experience in SQL, Python, Power BI and Tableau, working remotely as an analytics contractor for US companies.

- Today: product and growth analytics for clients in healthcare technology, fintech, consumer goods and technology services (SQL, Redshift, Databricks, Power BI, Tableau)
- Before: built the Foreign Exchange analytics function at XP Inc. from scratch, with 70+ Power BI dashboards
- Also: supply chain analytics at DHL and 7 months on-site at Bosch Rexroth in Charlotte, NC

## Case studies

Each one takes a kind of question I answer at work and rebuilds it from scratch on synthetic data. The data generator plants the true effect, so every README can show whether the method gets it right. No client data and no client code.

| Project | The question | What it shows | Stack |
|---|---|---|---|
| [acquisition-roas-funnel](https://github.com/vinniBiazon/acquisition-roas-funnel) | Which ad channel really pays back? | Signup funnel by UTM counting only eligible starts, ROAS by channel, 24-month value projection checked with a backtest | dbt, DuckDB, Python |
| [churn-reactivation-drivers](https://github.com/vinniBiazon/churn-reactivation-drivers) | Does the win-back email bring members back? | Churn and reactivation with window functions, a random holdout against click-based credit, retention heatmaps | dbt, DuckDB, Python |
| [feature-launch-placebo-test](https://github.com/vinniBiazon/feature-launch-placebo-test) | Did the launch work? | Seasonality adjustment, placebo dates, selection bias in a badge launch, an A/B test with sample ratio check | dbt, DuckDB, Python |
| [diff-in-diff-program-impact](https://github.com/vinniBiazon/diff-in-diff-program-impact) | Did the paid program work? | Difference-in-differences, parallel trends, placebo test, bootstrap intervals | SQL (DuckDB), Python |
| [earnings-estimator-model](https://github.com/vinniBiazon/earnings-estimator-model) | What should a panelist expect to earn? | Percentile model with trimming, calibrated multipliers and a small-sample fallback | SQL (DuckDB), Python |
| [PowerBI](https://github.com/vinniBiazon/PowerBI) | XP Foreign Exchange analytics | Power BI dashboards from XP (screenshots only, data hidden for privacy) | Power BI, DAX |

The three dbt projects run with `dbt build`: layered models, seeds, generic and custom data tests, and the study design in project `vars`.

LinkedIn: [linkedin.com/in/viniciusbiazon](https://www.linkedin.com/in/viniciusbiazon/)
