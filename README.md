# Impact of Generative AI on the Environment

A student project exploring the environmental impacts of generative AI, with a quantitative focus on energy consumption and a CRISP-DM workflow.

[Project dashboard](docs/dashboard.md) · [Scope and constraints](docs/project-scope.md) · [Data inventory](data/README.md) · [Sources](references/sources.md)

## Research question

What do available, verifiable datasets show about AI energy consumption, and what future consumption can be explored through forecasts or scenarios?

## Objectives

- Review evidence on energy, carbon emissions, water use and hardware impacts.
- Verify the provenance, units and suitability of the selected datasets.
- Clean suitable data and visualise historical patterns.
- Evaluate forecasts when a genuine time series is available; otherwise develop scenarios with explicit assumptions.
- Present findings, uncertainty and limitations.

Regional electricity and gas totals provide context. They cannot by themselves identify consumption caused by generative AI. A dataset filename or timestamp is not proof of measured historical trends.

## Repository guide

| Folder | Contents |
| --- | --- |
| data/raw/ | Original datasets |
| data/processed/ | Cleaned and aggregated outputs |
| notebooks/ | Numbered analysis notebooks |
| src/ | Reusable analysis code |
| references/ | Papers and source links |
| docs/ | Work plan, scope and meeting decisions |
| reports/figures/ | Figures for reports and slides |
| reports/presentations/ | Presentation and course materials |

## Current status

Project planning and source collection are finished. Analysis results have not yet been validated. Three working datasets are uploaded in `data/raw folder`. Literature review is finished, all necessary literature sources (pdfs, links) are in `references ` folder.

## Working method

1. Business understanding: agree the research question, scope and deliverables.
2. Data understanding: inspect sources, measurement boundaries and data quality.
3. Data preparation: document cleaning and aggregation; preserve raw inputs.
4. Modelling: start with a simple baseline; add machine learning only if justified.
5. Evaluation: use later held-out observations for forecasting and test scenario assumptions.
6. Communication: present results and limitations in readable figures and slides.

## Team workflow

Use the [dashboard](docs/dashboard.md) to assign owners, agree deadlines and review progress. Work on a branch for each task and ask a teammate to review changes. Link the deliverable before marking a task complete.

[Repository contributors](https://github.com/Ayaulyy/Impact-of-Generative-AI-on-Environment/graphs/contributors)

## Reproducibility

No executable analysis pipeline is configured yet. When analysis is added, document dependencies, software versions and run commands here. Keep reproducible steps in notebooks or scripts, and never commit credentials or private information.
