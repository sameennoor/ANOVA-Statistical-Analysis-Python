# Advanced ANOVA-Based Statistical Analysis Framework

This project is a Python-based statistical computing framework designed to perform advanced data analysis using multiple ANOVA techniques. It enables comparison between groups, evaluation of experimental datasets, and visualization of statistical results using graphs and plots.

## ⚡ Core Analytical Capabilities

The system isolates variance thresholds through four specialized mathematical processing modules:

* **Single-Factor Parametric Modeling (One-Way ANOVA):** Quantifies variance distribution across independent categorical cohorts utilizing continuous probability evaluation.
* **Dual-Factor Interaction Modeling (Two-Way ANOVA):** Dissects simultaneous main effects and interconnected cross-variable dependencies between distinct experimental matrices.
* **Within-Subject Longitudinal Tracks (Repeated Measures ANOVA):** Normalizes individual subject baselines to track sequential variance trends across continuous chronological intervals.
* **Conservative Post-Hoc Calibration (Scheffé’s Contrast Matrix):** Executes stringent, non-biased pairwise comparison sequences to safeguard against Type I error inflation during multi-group contrasts.

---

## 🔬 Architecture Breakdowns & Mathematical Implementations

### 1. Independent Factor Processing
* Evaluates population mean variations using structural cross-group matrices.
* Driven programmatically through optimized algorithms within `scipy.stats.f_oneway`.

### 2. Multi-Factor Dependency Engine
* Decouples compounding attributes to evaluate individual and combined feature impacts.
* Maps complex intersection points across overlapping data variables.

### 3. Subject-Isolated Trend Monitors
* Controls for intra-subject variability by monitoring individual entities over repetitive cycles.
* Managed programmatically via structural linear modeling in `Statsmodels.AnovaRM`.

### 4. Non-Parametric Pairwise Controls
* Deploys Scheffé’s continuous linear contrast methods for safe multi-group evaluations.
* Isolates exact variant locations post-rejection of the null hypothesis.

---

## 📊 Exploratory Visual Analytics

The pipeline translates abstract statistical metrics into production-ready analytical plots leveraging automated charting suites:
* **Distribution Density Matrices:** Continuous box-and-whisker plots isolating variance spread, median drift, and structural outliers.
* **Longitudinal Trajectory Plots:** Sequential line topologies tracking intra-subject behavior adjustments across conditions.
* **Automated Render Layers:** Native compilation utilizing object-oriented graphics pipelines via Matplotlib and Seaborn.

---

## ⚙️ Core Technical Stack
| ├── Engine Runtime     :  Python 3.x
|  ├── Data Wrangling     :  Pandas Core / NumPy Vectorization
|  ├── Compute Analytics  :  SciPy Stats / Statsmodels Linear Architecture
|  ├── Visual Framework   :  Matplotlib Pipelines / Seaborn Canvas

## 📂 Source Directory Topology
ANOVA/ 
│   ├── one_way_anova.py                # Independent single-factor matrix processing
│   ├── two_way_anova.py                # Interacting dual-factor variance evaluation
│   ├── repeated_measures.py            # Within-subject longitudinal tracking pipelines 
│   └── scheffe_post_hoc.py             # Conservative pairwise significance calibration
