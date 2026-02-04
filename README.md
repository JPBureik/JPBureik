# Hi, I'm Jan-Philipp (“JP”) Bureik 👋

I'm a quantitative software engineer (PhD in quantum physics) building production-grade Python libraries for **quantitative finance**:
  **robust statistical inference**, **higher-order dependence**, **streaming & observability**, and **performance-critical Python** (C/C++/Cython when needed).

- 📍 Paris, France
- 🧰 Python (advanced) · C/C++ (applied) · SQL · Linux
- 🔭 Interests: non-Gaussian statistics, higher-order moments, robust estimation under heavy tails, bootstrap resampling

---

## Featured projects

### 🔥 `crash-sensitivity-factor` — rolling higher-order co-moment estimation on equity returns (OSS)
Python library quantifying stock crash sensitivity via coskewness/cokurtosis betas with the market.
- Rolling estimators with robust heavy-tail handling: winsorization, MAD scaling, ridge shrinkage
- 95% test coverage, strict mypy, CI across Python 3.10–3.13
- Runnable synthetic demo (no external data needed)

➡️ https://github.com/JPBureik/crash-sensitivity-factor

### 🧭 `experiment-monitoring` — monitoring toolkit + turnkey deployment (OSS)
Driver-based Python monitoring library with calibration + spike-filter utilities, packaged with deployment scripts and a runbook.
- Designed for long-running operation (dashboards/alerts/retention ergonomics)
- Easy to extend via fully typed interfaces/ABCs

➡️ https://github.com/JPBureik/experiment-monitoring

### ⚡ Performance work
Optimized components for compute-intensive data analysis pipelines, with stable Python APIs.

**`mpviz`** — CPU multiprocessing with real-time progress visualization (OSS)
- Drop-in replacement for list comprehensions with automatic parallelization
- Per-core progress bars via enlighten
- 53 tests, strict mypy, CI across Python 3.11–3.14 + Linux/macOS/Windows

➡️ https://github.com/JPBureik/mpviz

**`fast-histogram-lookup`** — Cython kernel for large-scale correlation analysis
- ~40x speedup over pure Python; profiling-driven optimization for compute-intensive statistical workflows

➡️ https://github.com/JPBureik/fast-histogram-lookup

---

## What I value in engineering
- Deterministic, reproducible outputs; clear APIs; tests + CI
- Type safety as documentation (strict mypy)
- Profiling before optimizing
- Minimal operational burden ("someone else can run this")
- Careful handling of non-Gaussian data, outliers, and numerical stability

---

## Toolbox
- **Stats/data:** NumPy, pandas, SciPy, statsmodels, scikit-learn, boost-histogram
- **Time series / monitoring:** InfluxDB, Grafana
- **Perf:** Cython, Numba, vectorization, multiprocessing
- **Systems:** Linux, systemd, MySQL, Git, CMake

---

## Open to roles
I'm interested in **quant dev / quant research** roles working on:
time-series analytics, statistical estimation, robust inference, and performance.

📫 **Email:** jp.bureik@protonmail.com
