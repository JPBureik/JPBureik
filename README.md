# Hi, I'm Jan-Philipp (“JP”) Bureik 👋

I'm a research software engineer (PhD in quantum physics) focused on **quantitative finance / data-intensive research**:
  **robust statistical inference**, **higher-order dependence**, **streaming & observability**, and **performance-critical Python** (C/C++/Cython when needed).

- 📍 Paris, France
- 🧰 Python (advanced) · C/C++ (applied) · SQL · Linux
- 🔭 Interests: market microstructure & time series, heavy tails/outliers, UQ, profiling-led optimization

---

## Featured projects

### 🔥 `crash-sensitivity-factor` — crash-sensitivity signals from higher-order co-moments (OSS)
Python library quantifying stock crash sensitivity via coskewness/cokurtosis betas with the market.
- Robust estimation: winsorization, MAD scaling, ridge shrinkage
- 95% test coverage, strict mypy, CI across Python 3.10–3.13
- Runnable synthetic demo (no external data needed)

➡️ https://github.com/JPBureik/crash-sensitivity-factor

### 🧭 `experiment-monitoring` — monitoring toolkit + turnkey deployment (OSS)
Driver-based Python monitoring library with calibration + spike-filter utilities, packaged with deployment scripts and a runbook.
- Designed for long-running operation (dashboards/alerts/retention ergonomics)
- Easy to extend via fully typed interfaces/ABCs

➡️ https://github.com/JPBureik/experiment-monitoring

### ⚡ Performance work
Optimized components for compute-intensive workflows, with stable Python APIs.

**`multiproc`** — CPU multiprocessing with real-time progress tracking (OSS)
- Drop-in replacement for list comprehensions with automatic parallelization
- Per-core progress bars via enlighten
- 53 tests, strict mypy, CI across Python 3.11–3.14 + Linux/macOS/Windows

➡️ https://github.com/JPBureik/Multiproc

**`fast-histogram-lookup`** — Cython-optimized histogram operations
- Compiled components for hot loops with profiling-driven optimization

➡️ https://github.com/JPBureik/fast-histogram-lookup

---

## What I value in engineering
- Reproducible results, clear APIs, tests + CI
- Type safety as documentation (strict mypy)
- Profiling before optimizing
- Minimal operational burden ("someone else can run this")
- Careful handling of edge cases (missing data, outliers, stability)

---

## Toolbox
- **Stats/data:** NumPy, pandas, SciPy, statsmodels, scikit-learn
- **Time series / monitoring:** InfluxDB, Grafana
- **Perf:** Cython, vectorization, multiprocessing
- **Systems:** Linux, systemd, MySQL, Git, CMake

---

## Open to roles
I’m interested in **quant dev / quant research engineering** and **research software engineering** roles working on:
data systems, streaming/time-series analytics, robust inference, and performance.

📫 **Email:** jp.bureik@protonmail.com
