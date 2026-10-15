# Mark Cameron Nelson, PhD

I am a quantitative scientist building Python and SQL tools for data analysis, machine learning, and reliable data pipelines. My background in biomedical research includes statistical modeling, network analysis, and multimodal neuroimaging. I turn complex questions and datasets into tested software, reproducible analyses, and interactive applications.

Based in Bend, Oregon. Open to data science, data engineering, applied machine learning, software engineering, and quantitative research opportunities, with particular interest in biomedical and healthcare applications.

## Core expertise

* **Programming and software:** Python, SQL, MATLAB, Bash, Linux, Git, automated testing, GitHub Actions
* **Data engineering and analytics:** DuckDB, Snowflake, dbt, ETL pipelines, data modeling, automated quality checks, Streamlit dashboards
* **Statistics and machine learning:** Regression, predictive modeling, feature engineering, cross-validation, dimensionality reduction, latent variable modeling, permutation testing
* **Language models and retrieval:** Hugging Face Transformers, LangChain, LangGraph, semantic search, lexical search, zero-shot classification, quantitative evaluation
* **Network science:** Graph theory, communication models, spectral analysis, community detection
* **Scientific computing and biomedical data:** HPC workflows, parallel computing, multimodal MRI, diffusion MRI, fMRI, MEG, EEG, and behavioral data 

## Featured projects

### CityFlow: SQL Analytics Pipeline & Cloud Dashboard

**Problem:** Turn millions of NYC taxi records into reliable, explorable metrics for trip activity, route demand, travel times, and fares.

**My role:** Designed and built the complete data workflow: Python ingestion, SQL data modeling with dbt, automated quality checks, migration from DuckDB to Snowflake, validation across both engines, and deployment of an interactive public dashboard. Configured Snowflake access controls, compute limits, and resource cleanup.

**Technologies:** Python, SQL, DuckDB, dbt, Snowflake, Streamlit, pandas, pytest, GitHub Actions

**Value:** Processed 11.2 million trips into tested analytical tables and an accessible dashboard. All 8 dbt models and 33 data tests passed, and all three analytical marts matched between DuckDB and Snowflake. Verified every published dashboard value against the local analytics. The deployed app uses an aggregate snapshot, keeping it available after cloud resources and database credentials were removed. Demonstrates practical data engineering, SQL analytics, automated validation, cloud cost management, and delivery of a usable product.

[Project Repository](https://github.com/MarkNelson86/cityflow) |
[Live Dashboard](https://cityflow-mark.streamlit.app/)

### Biomedical Literature Search & Classification with Python, SQL & Transformers

**Problem:** Build and evaluate biomedical literature search and topic classification tools, measuring whether pretrained transformers improve retrieval over a conventional keyword-search baseline.

**My role:** Designed and built the complete workflow: PubMed data acquisition, benchmark curation, SQLite storage and indexing, lexical and semantic search, zero-shot topic classification, quantitative evaluation, and error analysis.

**Technologies:** Python, SQL/SQLite, FTS5/BM25, Hugging Face Transformers, Sentence Transformers (MiniLM), DeBERTa, PyTorch, pandas, scikit-learn, NCBI E-utilities

**Value:** Created a reproducible 80-paper benchmark to compare search methods and evaluate classification without task-specific training. On this benchmark, FTS5/BM25 retrieval achieved higher precision at five results than MiniLM semantic search (P@5: 1.00 vs. 0.95), while zero-shot DeBERTa classification achieved 87.5% accuracy. Demonstrates SQL-backed search, practical use of pretrained models, and evidence-based selection of model complexity.

[Project Repository](https://github.com/MarkNelson86/biomedical-literature-search-hf-sql)

### Predicting Brain Connectivity with Python & Machine Learning

**Problem:** Test whether individual structural brain measurements improve predictions of functional connectivity beyond the average connectivity pattern learned from training participants.

**My role:** Designed and built the complete modeling workflow: multimodal data validation, participant-based cross-validation, linear and nonlinear models, controls against data leakage, performance evaluation, automated tests, and a public synthetic-data demo.

**Technologies:** Python, NumPy, pandas, SciPy, statsmodels, scikit-learn, Ridge regression, gradient boosting, neural networks, pytest, GitHub Actions

**Value:** Benchmarked prediction models across two neuroimaging cohorts. In the 45-participant MICs benchmark, the training-average baseline outperformed residual Ridge, gradient boosting, and a small neural network, showing that added model complexity did not improve prediction under the tested conditions. Demonstrates careful validation of correlated biomedical data and reproducible software engineering, supported by 47 automated tests and a synthetic demo that runs without private data.

[Project Repository](https://github.com/MarkNelson86/biomedical-literature-search-hf-sql)

### Microstructure–Function Modeling in Human Brain Networks

**Problem:** Determine how white-matter microstructure contributes to large-scale functional connectivity across imaging modalities and neural timescales.

**My role:** Led the analytical program from research design through model implementation, validation, visualization, publication, and reusable software development.

**Methods:** Graph communication models, hierarchical regression, permutation testing, spectral analysis, community detection, multimodal integration.

**Technologies:** MATLAB, Python, Git, neuroimaging and network-analysis tools.

**Outputs:** 10 peer-reviewed papers (3 first author), doctoral thesis, 9 conference abstracts, and 3 reproducible analytical packages.

[Repository](https://github.com/TardifLab/Modeling-Myelin-FC) | 
[Publication](https://doi.org/10.1038/s42003-026-09813-6) |
[Repository](https://github.com/TardifLab/myelin-communication-FC) | 
[Publication](https://doi.org/10.64898/2026.03.22.713515) |
[Repository](https://github.com/TardifLab/Weighted-SC-Networks) | 
[Publication](https://doi.org/10.1162/netn_a_00330) |
[Thesis](https://doi.org/10.13140/RG.2.2.29214.09289)

### Reproducible Multimodal Neuroimaging Infrastructure

**Problem:** Adapt and stabilize a complex multimodal imaging pipeline for multiple independent datasets, divergent workflows, and shared lab infrastructure.

**My role:** Designed centralized configuration, cluster and local processing wrappers, module-specific overrides, future extension points, dependency controls, and developer-facing documentation.

**Technologies:** Bash, Linux, HPC, Git, containers, configuration management, micapipe.

**Short-term value:** Improved workflow consistency, flexibility, and efficiency.

**Long-term value:** Provided a framework supporting extension and reuse by other researchers, as well as standardization of custom tools for uptake by the scientific community.

[Adapted pipeline repository](https://github.com/TardifLab/micapipe-lab) | [Core pipeline documentation](https://micapipe.readthedocs.io/en/latest/)

### Large-Scale EEG Memory Modeling and Data Curation

**Problem:** Relate memory performance to electrophysiological signals and prepare large EEG and behavioral dataset for publication.

**My role:** Organized, quality-controlled, and analyzed EEG and behavioral data from approximately 1,000 participants across seven tasks.

**Methods:** Signal processing, dimensionality reduction, latent-variable modeling, predictive analysis, and multivariate statistics.

**Technologies:** MATLAB, EEGLAB, BIDS, reproducible data processing.



## Publications and professional profiles

[LinkedIn](https://www.linkedin.com/in/mark-cameron-nelson/) | 
[ORCID](https://orcid.org/0000-0003-1074-0814) | 
[Google Scholar](https://scholar.google.com/citations?user=4GPxeAUAAAAJ&hl=en&oi=ao) | 
[ResearchGate](https://www.researchgate.net/profile/Mark-Nelson-40/research)

## Contact

Bend, Oregon
[markuscameron86@gmail.com](mailto:markuscameron86@gmail.com)
