# Hands-On AI Agents, Level 3: Production-Ready Agents

**Free code companion** for the book by Exobean Engineering: the book's code, a notebook for every lesson, and self-grading exercises with answers.

## [⬇ Download the code companion](https://github.com/exobean/ai-agents-level3/releases/latest/download/prodlab-companion.zip)

`prodlab-companion.zip`. No account or sign-in needed.

## Set up in four steps

1. Unzip the file you downloaded.
2. Install [uv](https://docs.astral.sh/uv/), a free Python tool (it also installs Python for you).
3. Open a terminal inside the unzipped folder and run `uv sync`.
4. Check everything works: `uv run python -m shopassist.doctor`

Grade a lesson's exercises any time: `uv run pytest exercises/<lesson>`. The book explains every step with pictures.

## Browser only? Use Google Colab

Click **Open in Colab** next to your lesson, then run the first cell. It downloads the companion for you; then run the rest in order.

## Lesson notebooks

| Lesson | Notebook |
| --- | --- |
| 1.1 From function to service | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/exobean/ai-agents-level3/blob/main/notebooks/m01_l01_service.ipynb) |
| 1.2 Configuration and secrets | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/exobean/ai-agents-level3/blob/main/notebooks/m01_l02_config.ipynb) |
| 1.3 Versioned releases and rollback | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/exobean/ai-agents-level3/blob/main/notebooks/m01_l03_releases.ipynb) |
| 1.4 Deploy: containers, health and rolling updates | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/exobean/ai-agents-level3/blob/main/notebooks/m01_l04_deploy.ipynb) |
| 2.1 Structured logs, without personal data | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/exobean/ai-agents-level3/blob/main/notebooks/m02_l01_logs.ipynb) |
| 2.2 Traces: where the time goes | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/exobean/ai-agents-level3/blob/main/notebooks/m02_l02_traces.ipynb) |
| 2.3 Metrics: averages hide the slow tail | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/exobean/ai-agents-level3/blob/main/notebooks/m02_l03_metrics.ipynb) |
| 2.4 SLOs, error budgets and alerts | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/exobean/ai-agents-level3/blob/main/notebooks/m02_l04_slos.ipynb) |
| 3.1 Grading answers with a judge | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/exobean/ai-agents-level3/blob/main/notebooks/m03_l01_judges.ipynb) |
| 3.2 Calibrate the judge against people | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/exobean/ai-agents-level3/blob/main/notebooks/m03_l02_calibrate.ipynb) |
| 3.3 Regression gates in CI | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/exobean/ai-agents-level3/blob/main/notebooks/m03_l03_regressions.ipynb) |
| 3.4 Shadow tests on real traffic | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/exobean/ai-agents-level3/blob/main/notebooks/m03_l04_shadow.ipynb) |
| 4.1 What an answer costs | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/exobean/ai-agents-level3/blob/main/notebooks/m04_l01_cost.ipynb) |
| 4.2 Caching, safely | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/exobean/ai-agents-level3/blob/main/notebooks/m04_l02_cache.ipynb) |
| 4.3 Faster answers: parallel parts | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/exobean/ai-agents-level3/blob/main/notebooks/m04_l03_latency.ipynb) |
| 4.4 Rate limits and budgets | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/exobean/ai-agents-level3/blob/main/notebooks/m04_l04_limits.ipynb) |
| 5.1 Prompt injection, direct and hidden | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/exobean/ai-agents-level3/blob/main/notebooks/m05_l01_injection.ipynb) |
| 5.2 Permissions: who may see what | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/exobean/ai-agents-level3/blob/main/notebooks/m05_l02_permissions.ipynb) |
| 5.3 Output guards: the last line of defence | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/exobean/ai-agents-level3/blob/main/notebooks/m05_l03_output.ipynb) |
| 5.4 Lab: red-team the assistant | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/exobean/ai-agents-level3/blob/main/notebooks/m05_l04_redteam.ipynb) |
| 6.1 Timeouts, retries and deadlines | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/exobean/ai-agents-level3/blob/main/notebooks/m06_l01_timeouts.ipynb) |
| 6.2 Circuit breakers and fallbacks | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/exobean/ai-agents-level3/blob/main/notebooks/m06_l02_breaker.ipynb) |
| 6.3 People in the loop: the review queue | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/exobean/ai-agents-level3/blob/main/notebooks/m06_l03_review_queue.ipynb) |
| 6.4 Incidents: detect, mitigate, learn | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/exobean/ai-agents-level3/blob/main/notebooks/m06_l04_incidents.ipynb) |
| 7.1 Capstone: ShopAssist in production | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/exobean/ai-agents-level3/blob/main/notebooks/m07_l01_assemble.ipynb) |
| 7.2 Capstone: launch day | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/exobean/ai-agents-level3/blob/main/notebooks/m07_l02_launch_day.ipynb) |
| 7.3 Capstone: go or no go | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/exobean/ai-agents-level3/blob/main/notebooks/m07_l03_go_live.ipynb) |

## Licence

Copyright 2026 Exobean Engineering. Free for your own learning and projects; see `LICENSE.txt`. For learning purposes only.
