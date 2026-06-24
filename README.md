# Palash Gupta - B.Engineering (EE,EC,CS), MSc

Data Scientist (analysis/experimentation) building decision-support models and clear, visual analytics for real-world problems.

- Strengths: Experiment Design, Feature Engineering, Robust Validation, Model Building, and Stakeholder Translation.
- Domains: Finance, Healthcare, Business, Retail/Commercial Analytics, and Sports Analytics
- Main Languages: Python, R, SQL, Typescript, and React

## Contact

- Email: <palashcscs@outlook.com>
- LinkedIn: [in/pgds](https://www.linkedin.com/in/pgds/)
- GitHub: [PGupta-Git](https://github.com/PGupta-Git)

## How I work (analysis/experimentation)

- Start with a decision and a measurable target (KPI definition comes first).
- Establish baselines, define leakage-safe splits, and validate with time-aware backtesting when appropriate.
- Prefer simple, explainable models when they perform; add complexity only when it wins on validated metrics.
- Communicate uncertainty (calibration, intervals, sensitivity checks) and translate results into concrete actions.

## Publications

- **Published Article:** [A pragmatic, parallel-arm, randomised trial on the effects of two repeated-sprint training protocols on fitness outcomes in semi-professional male soccer players: preliminary report](https://doi.org/10.1080/24733938.2026.2684071) (*Science and Medicine in Football*, 2026) | [Data & Code Repository](https://github.com/PGupta-Git/Gupta_et_al_RST_Paper_Submission)
- ORCID: <https://orcid.org/0009-0000-0172-4009>

## Open Source Contributions

Active contributor to popular open-source projects, libraries, and desktop utilities:

- **[brilliantnz/flickernaut](https://github.com/brilliantnz/flickernaut)** (GNOME Shell Extension adding custom Nautilus context menu entries)
  - **Invalid Apps & Desktop Files Fix ([PR #9](https://github.com/brilliantnz/flickernaut/pull/9))**: Resolved a critical bug causing extension crashes by implementing robust `try-except` error handling for invalid or missing desktop files (handling null `Gio.DesktopAppInfo` returns).
  - **Duplicate Preferences Entries Fix ([PR #9](https://github.com/brilliantnz/flickernaut/pull/9))**: Prevented application entries from appearing twice in the preferences dialog by ensuring the chooser respects the `NoDisplay=true` desktop configuration.
- **[posit-dev/positron](https://github.com/posit-dev/positron)** (Open-source data science IDE built on VS Code by Posit)
  - **Console "Start Session" Button Spacing Fix ([PR #14381](https://github.com/posit-dev/positron/pull/14381) → [merged as PR #14445](https://github.com/posit-dev/positron/pull/14445))**: Fixed browser UA default padding on a native `<button>` used inline in `emptyConsole.css`, restoring flush baseline alignment with surrounding sentence text (fixes [#14155](https://github.com/posit-dev/positron/issues/14155)). Positron's CI requires non-fork PRs; a maintainer applied the commits to a new PR with full credit.
  - **Help Pane Find Widget — Enter Key Navigation ([PR #14380](https://github.com/posit-dev/positron/pull/14380) → [merged as PR #14444](https://github.com/posit-dev/positron/pull/14444))**: Wired plain Enter and Shift+Enter in the shared webview find widget to advance and reverse matches; removed a post-find focus redirect so the Find input retains focus after navigation (fixes [#12921](https://github.com/posit-dev/positron/issues/12921)). Carried into a non-fork PR by a contributor with credited authorship.
- **[can1357/oh-my-pi](https://github.com/can1357/oh-my-pi)** (AI coding harness — MCP server orchestration and provider routing)
  - **OpenCode MCP Array Command & Environment Key Fix ([PR #3181](https://github.com/can1357/oh-my-pi/pull/3181), fixes [Issue #3180](https://github.com/can1357/oh-my-pi/issues/3180))**: Diagnosed and fixed two silent bugs in the OpenCode discovery provider: array-style `command` entries coerced to a comma-joined string causing `ENOENT` on spawn; `environment` key silently ignored in favour of `env` only. oh-my-pi requires vouched contributors, so the PR was closed and the owner implemented the equivalent fix ([PR #3182](https://github.com/can1357/oh-my-pi/pull/3182), merged 2026-06-21), explicitly crediting the issue diagnosis.
  - **Claude 4.6 Wire-ID Routing Fix on google-antigravity ([Issue #3067](https://github.com/can1357/oh-my-pi/issues/3067))**: Diagnosed two Claude 4.6 failure modes: (1) 404 from `thinkingPair` routing Sonnet thinking efforts to a non-existent `-thinking` wire ID the backend does not expose; (2) 400 from `maxOutputTokens: 65536` exceeding the backend's 64000 cap. The maintainer's follow-up fix commit [`47cc464`](https://github.com/can1357/oh-my-pi/commit/47cc46496209e06f89945f9b4515f22e621f71b6) (merged 2026-06-19) explicitly credits *"@PGupta-Git"* in the commit message and the shipped regression test is named `issue-3067-repro.test.ts`.
- **[andrewRowlinson/mplsoccer](https://github.com/andrewRowlinson/mplsoccer)** (Matplotlib-based soccer visualization library)
  - **Speedometer & Gauge Charts ([PR #118](https://github.com/andrewRowlinson/mplsoccer/pull/118))**: Ported and integrated the `Speedometer` class into mplsoccer's API patterns (based on the original [znstrider/speedo](https://github.com/znstrider/speedo) library; implements Issue #16), enabling highly customizable gauge and speedometer charts. PR open, pending maintainer review.
  - **Curved Radar Text Labels ([PR #120](https://github.com/andrewRowlinson/mplsoccer/pull/120))**: Authored curved label support for radar charts along circular arcs using vector glyph paths (`TextPath`/`PathPatch`) and `TextToPath` metrics, resolving rounding jitter (fixes Issue #35). Supports multi-line curved labels and auto-flipping for bottom-half readability. PR open, all checks passing, pending maintainer review.
  - **Wikipedia Rate-Limiting Fixes ([PR #120](https://github.com/andrewRowlinson/mplsoccer/pull/120))**: Resolved build failures in docstring gallery examples by standardizing Wikipedia thumbnail sizes and adding proper User-Agent headers to requests.
- **[ageron/handson-mlp](https://github.com/ageron/handson-mlp)** (Aurélien Géron's Hands-On Machine Learning book repository)
  - **Full Polars Migration — Community Fork ([polars_integration branch](https://github.com/PGupta-Git/handson-mlp/tree/polars_integration))**: Maintaining the community-endorsed Polars variant of all notebook exercises (19 chapters + appendices), with a dedicated `tools_polars.ipynb` added. The upstream author confirmed he won't maintain both variants but endorsed the fork ([Issue #23](https://github.com/ageron/handson-mlp/issues/23)). [PR #41](https://github.com/ageron/handson-mlp/pull/41) (open, awaiting merge) adds a one-line README pointer from the upstream repo to this branch.

## Toolbox

### Languages

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-1F2937?style=for-the-badge&logo=postgresql&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)

### Development Tools

![uv](https://img.shields.io/badge/uv-DE5FE9?style=for-the-badge&logo=astral&logoColor=white)
![renv](https://img.shields.io/badge/renv-75AADB?style=for-the-badge&logo=r&logoColor=white)
![Ruff](https://img.shields.io/badge/Ruff-FCC21B?style=for-the-badge&logo=ruff&logoColor=black)
![Bun](https://img.shields.io/badge/Bun-14151A?style=for-the-badge&logo=bun&logoColor=white)
![Quarto](https://img.shields.io/badge/Quarto-75AADB?style=for-the-badge&logo=quarto&logoColor=white)
![Copier](https://img.shields.io/badge/Copier-1F2937?style=for-the-badge&logo=copier&logoColor=white)
![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=for-the-badge&logo=pydantic&logoColor=white)

### IDEs

![Positron](https://img.shields.io/badge/Positron-6FB3D2?style=for-the-badge&logo=posit&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)
![PyCharm](https://img.shields.io/badge/PyCharm-000000?style=for-the-badge&logo=pycharm&logoColor=white)

### Data Science

![Polars](https://img.shields.io/badge/Polars-CD792C?style=for-the-badge&logo=polars&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Ibis](https://img.shields.io/badge/Ibis-FF6B6B?style=for-the-badge&logo=python&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![CatBoost](https://img.shields.io/badge/CatBoost-F50A4D?style=for-the-badge&logo=catboost&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![marimo](https://img.shields.io/badge/marimo-358A30?style=for-the-badge&logo=python&logoColor=white)
![LightGBM](https://img.shields.io/badge/LightGBM-2980B9?style=for-the-badge&logo=python&logoColor=white)
![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=for-the-badge&logo=duckdb&logoColor=black)
![Optuna](https://img.shields.io/badge/Optuna-4158D0?style=for-the-badge&logo=python&logoColor=white)
![statsmodels](https://img.shields.io/badge/statsmodels-4A90D9?style=for-the-badge&logo=python&logoColor=white)
<a href="https://cran.r-project.org/package=tidyverse"><img src="assets/r/tidyverse.png" height="44" alt="tidyverse" /></a>
<a href="https://cran.r-project.org/package=tidymodels"><img src="assets/r/tidymodels.png" height="44" alt="tidymodels" /></a>
<a href="https://cran.r-project.org/package=mlr3"><img src="assets/r/mlr3.png" height="44" alt="mlr3" /></a>
<a href="https://cran.r-project.org/package=easystats"><img src="assets/r/easystats.png" height="44" alt="easystats" /></a>

### Visualization

![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=plotly&logoColor=white)
![plotnine](https://img.shields.io/badge/plotnine-4A90D9?style=for-the-badge&logo=python&logoColor=white)
![Altair](https://img.shields.io/badge/Altair-F9A825?style=for-the-badge&logo=python&logoColor=white)
![seaborn](https://img.shields.io/badge/seaborn-4C72B0?style=for-the-badge&logo=python&logoColor=white)
![Great Tables](https://img.shields.io/badge/Great%20Tables-1F7A8C?style=for-the-badge&logo=python&logoColor=white)

### Data Validation

![Pandera](https://img.shields.io/badge/Pandera-1A1A2E?style=for-the-badge&logo=python&logoColor=white)
![Pointblank](https://img.shields.io/badge/Pointblank-1F7A8C?style=for-the-badge&logo=python&logoColor=white)
![Dataframely](https://img.shields.io/badge/Dataframely-2C3E50?style=for-the-badge&logo=python&logoColor=white)
![Great Expectations](https://img.shields.io/badge/Great%20Expectations-FF6B35?style=for-the-badge&logo=python&logoColor=white)

### MLOps

![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=for-the-badge&logo=mlflow&logoColor=white)
![DVC](https://img.shields.io/badge/DVC-F50A4D?style=for-the-badge&logo=dvc&logoColor=white)
![Prefect](https://img.shields.io/badge/Prefect-024DFD?style=for-the-badge&logo=prefect&logoColor=white)

### Reporting & Apps

![Shiny](https://img.shields.io/badge/Shiny-1E6BD6?style=for-the-badge&logo=rstudio&logoColor=white)
![Dash](https://img.shields.io/badge/Dash-111111?style=for-the-badge&logo=plotly&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-111111?style=for-the-badge&logo=nextdotjs&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)

### Data Engineering

![BigQuery](https://img.shields.io/badge/BigQuery-4285F4?style=for-the-badge&logo=googlebigquery&logoColor=white)
![Google Cloud Storage](https://img.shields.io/badge/Google%20Cloud%20Storage-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)
![Amazon Redshift](https://img.shields.io/badge/Amazon%20Redshift-8C4FFF?style=for-the-badge&logo=amazonredshift&logoColor=white)
![Amazon S3](https://img.shields.io/badge/Amazon%20S3-569A31?style=for-the-badge&logo=amazons3&logoColor=white)
![Azure Synapse](https://img.shields.io/badge/Azure%20Synapse-0089D6?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Azure Blob Storage](https://img.shields.io/badge/Azure%20Blob%20Storage-0089D6?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Apache Airflow](https://img.shields.io/badge/Apache%20Airflow-017CEE?style=for-the-badge&logo=apacheairflow&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=for-the-badge&logo=dbt&logoColor=white)
![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=for-the-badge&logo=databricks&logoColor=white)
![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=for-the-badge&logo=snowflake&logoColor=white)
![Apache Spark](https://img.shields.io/badge/Apache%20Spark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white)
![Dagster](https://img.shields.io/badge/Dagster-654FF0?style=for-the-badge&logo=dagster&logoColor=white)

### Engineering

![Postgres](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Neon](https://img.shields.io/badge/Neon-00E699?style=for-the-badge&logo=neon&logoColor=black)
![Drizzle ORM](https://img.shields.io/badge/Drizzle%20ORM-C5F74F?style=for-the-badge&logo=drizzle&logoColor=black)
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![lakeFS](https://img.shields.io/badge/lakeFS-0080FF?style=for-the-badge&logo=lakefs&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Cloud Run](https://img.shields.io/badge/Cloud%20Run-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)
![Cloud VM](https://img.shields.io/badge/Cloud%20VM-FF6F00?style=for-the-badge&logo=googlecloud&logoColor=white)

## Featured work

| Project | What it shows | Links |
| --- | --- | --- |
| Repeated sprint training trial (research) | Statistical rigor, reproducible analysis artifacts | [Open Access Paper Published in Science and Medicine in Football](https://doi.org/10.1080/24733938.2026.2684071)<br><br>[Data & Code Repo](https://github.com/PGupta-Git/Gupta_et_al_RST_Paper_Submission)<br><br>![R](https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white) ![renv](https://img.shields.io/badge/renv-75AADB?style=for-the-badge&logo=r&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-1F2937?style=for-the-badge&logo=postgresql&logoColor=white) <a href="https://cran.r-project.org/package=tidyverse"><img src="assets/r/tidyverse.png" height="44" alt="tidyverse" /></a> <a href="https://cran.r-project.org/package=tidymodels"><img src="assets/r/tidymodels.png" height="44" alt="tidymodels" /></a> <a href="https://cran.r-project.org/package=mlr3"><img src="assets/r/mlr3.png" height="44" alt="mlr3" /></a> <a href="https://cran.r-project.org/package=easystats"><img src="assets/r/easystats.png" height="44" alt="easystats" /></a> |
| Drill Design App (production) | Product thinking, data modeling, shipping a real app | <https://github.com/PGupta-Git/case-study-drill-design-app><br><br><https://www.drilldesignapp.com><br><br>![Next.js](https://img.shields.io/badge/Next.js-111111?style=for-the-badge&logo=nextdotjs&logoColor=white) ![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white) ![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-0F172A?style=for-the-badge&logo=tailwindcss&logoColor=38BDF8) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white) ![Vercel](https://img.shields.io/badge/Vercel-111111?style=for-the-badge&logo=vercel&logoColor=white) ![Bun](https://img.shields.io/badge/Bun-14151A?style=for-the-badge&logo=bun&logoColor=white) ![Vitest](https://img.shields.io/badge/Vitest-1F2937?style=for-the-badge&logo=vitest&logoColor=6E9F18) ![Drizzle ORM](https://img.shields.io/badge/Drizzle%20ORM-C5F74F?style=for-the-badge&logo=drizzle&logoColor=black) ![Neon](https://img.shields.io/badge/Neon-00E699?style=for-the-badge&logo=neon&logoColor=black) |
| Off-ball movement metric & player similarity (Premier League) | Metric design from raw tracking data, dual-signal similarity framework, structural-null semantics, sensitivity checks, visual storytelling | <https://github.com/PGupta-Git/case-study-btla-framework><br><br>![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) ![uv](https://img.shields.io/badge/uv-DE5FE9?style=for-the-badge&logo=astral&logoColor=white) ![Polars](https://img.shields.io/badge/Polars-CD792C?style=for-the-badge&logo=polars&logoColor=white) ![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white) ![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=for-the-badge&logo=scipy&logoColor=white) ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white) ![seaborn](https://img.shields.io/badge/seaborn-4C72B0?style=for-the-badge&logo=python&logoColor=white) ![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=for-the-badge&logo=mlflow&logoColor=white) ![DVC](https://img.shields.io/badge/DVC-F50A4D?style=for-the-badge&logo=dvc&logoColor=white) ![Pandera](https://img.shields.io/badge/Pandera-1A1A2E?style=for-the-badge&logo=python&logoColor=white) |
| Player availability & decision support | KPI redesign, feature engineering, time-aware validation, decision framing | <https://github.com/PGupta-Git/case-study-player-availability-decision-support><br><br>![R](https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white) ![renv](https://img.shields.io/badge/renv-75AADB?style=for-the-badge&logo=r&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-1F2937?style=for-the-badge&logo=postgresql&logoColor=white) <a href="https://cran.r-project.org/package=tidyverse"><img src="assets/r/tidyverse.png" height="44" alt="tidyverse" /></a> <a href="https://cran.r-project.org/package=tidymodels"><img src="assets/r/tidymodels.png" height="44" alt="tidymodels" /></a> <a href="https://cran.r-project.org/package=mlr3"><img src="assets/r/mlr3.png" height="44" alt="mlr3" /></a> <a href="https://cran.r-project.org/package=easystats"><img src="assets/r/easystats.png" height="44" alt="easystats" /></a> ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) ![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=for-the-badge&logo=mlflow&logoColor=white) ![DVC](https://img.shields.io/badge/DVC-F50A4D?style=for-the-badge&logo=dvc&logoColor=white) ![Pandera](https://img.shields.io/badge/Pandera-1A1A2E?style=for-the-badge&logo=python&logoColor=white) |
| Tactical / recruitment / performance analysis | Benchmarking, robustness checks, communication through visuals | <https://github.com/PGupta-Git/case-study-tactical-recruitment-performance-analysis><br><br>![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) ![uv](https://img.shields.io/badge/uv-DE5FE9?style=for-the-badge&logo=astral&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-1F2937?style=for-the-badge&logo=postgresql&logoColor=white) ![pandas](https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white) ![Polars](https://img.shields.io/badge/Polars-CD792C?style=for-the-badge&logo=polars&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white) ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white) ![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=for-the-badge&logo=mlflow&logoColor=white) ![DVC](https://img.shields.io/badge/DVC-F50A4D?style=for-the-badge&logo=dvc&logoColor=white) ![Pandera](https://img.shields.io/badge/Pandera-1A1A2E?style=for-the-badge&logo=python&logoColor=white) |
| Open-data experimentation lab | Public code: clean DS workflow, evaluation, visual storytelling | <https://github.com/PGupta-Git/open-football-experimentation-lab><br><br>![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) ![uv](https://img.shields.io/badge/uv-DE5FE9?style=for-the-badge&logo=astral&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-1F2937?style=for-the-badge&logo=postgresql&logoColor=white) ![pandas](https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white) ![Polars](https://img.shields.io/badge/Polars-CD792C?style=for-the-badge&logo=polars&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white) ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white) |

Note: case studies are anonymised (organisation names and private code/data are omitted).

## Selected impact

- Designed a novel geometric metric (BtLA) from 25Hz optical tracking data to profile a player's off-ball movement between lines, with continuous passing-lane openness scoring and segment-aware smoothing (see [BtLA Framework Case Study](https://github.com/PGupta-Git/case-study-btla-framework)).
- Built a dual-signal player similarity framework (cosine on movement shape + Euclidean on scaled level/volume) across a full season of Premier League event data, bridging tracking and event data paradigms (see [BtLA Framework Case Study](https://github.com/PGupta-Git/case-study-btla-framework)).
- Built non-linear models on high-frequency biometric telemetry to separate signal from noise and predict failure-mode risk (injury-risk proxy; see [Player Availability Case Study](https://github.com/PGupta-Git/case-study-player-availability-decision-support)).
- Engineered new "availability" features with domain experts, replacing legacy KPIs with more predictive signals (see [Player Availability Case Study](https://github.com/PGupta-Git/case-study-player-availability-decision-support)).
- Built forecasting models and automated reporting workflows, saving ~15 hours/week and reducing data retrieval latency by ~30%.
- Delivered executive dashboards for decision-making (market sentiment, product performance, performance monitoring; see [Drill Design App](https://github.com/PGupta-Git/case-study-drill-design-app) and [Tactical/Recruitment Case Study](https://github.com/PGupta-Git/case-study-tactical-recruitment-performance-analysis)).
- Led cross-functional delivery (Agile/Scrum) and bridged data engineering and non-technical stakeholders.
