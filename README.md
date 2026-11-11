# Ziyi Wang | Academic Portfolio

**Data Science · Machine Learning · Natural Language Processing · Responsible AI**

Welcome to my academic portfolio. This repository is the entry point to my selected research and coursework projects in data science, statistical learning and artificial intelligence. It brings together my independent MSc dissertation and four supplementary projects, each maintained in its own repository.

My academic background combines a **Master of Data Science (Distinction) from Durham University** with undergraduate training in architecture. My current research interests centre on machine learning and deep learning, particularly generative AI, large language models and multimodal learning.

---

## Research interests

- Generative AI and large language models
- Multimodal learning
- Deep learning and natural language processing
- Applied machine learning and statistical modelling
- Responsible AI, algorithmic bias and fairness

## Education

| Qualification | Institution | Details |
|---|---|---|
| **MSc Data Science** | Durham University | **Distinction**, 2025 |
| **BArch Architecture** | Tianjin Chengjian University | 2019–2024; GPA: 85.81/100 |

---

## Selected research and academic projects

The MSc dissertation is my primary independent research project. The other repositories provide additional examples of statistical analysis, supervised and unsupervised learning, collaborative modelling and critical writing on AI ethics.

### 1. MSc Dissertation — Human Values in Political Discourse

**Lexical Rules or Learned Representations? Assessing Dictionary and Machine Learning Models of Human Values in Political Discourse**

[Open dissertation repository](https://github.com/fifi-run/research-project) · [Research methodology](https://github.com/fifi-run/research-project/blob/main/docs/METHODOLOGY.md)

An independent research project comparing a theory-driven Personal Values Dictionary (PVD) with the transformer-based ValuesML model for detecting human values in political speeches.

**Research focus**
- Compare dictionary-based and contextual transformer-based approaches in a common ten-category label space.
- Examine sentence-level and paragraph-level text representations.
- Evaluate hard and soft PVD score binarisation strategies.
- Analyse precision, recall, macro-F1 and accuracy at aggregate and category levels.

**Methods and tools:** R, NLP, transformer-based model outputs, multi-label evaluation, statistical analysis.

**Reported finding:** ValuesML achieves the highest macro-F1 in both sentence-level and paragraph-level comparisons in the dissertation's reported experiments. The dissertation also finds that paragraph context substantially improves PVD performance.

**Research note:** The repository documents the experimental design, reported results and implementation caveats. It does not claim to train a new transformer architecture from scratch, and the original analysis scripts do not yet provide one verified end-to-end reproduction command.

### 2. Atmospheric Gas Data Analysis

[Open project repository](https://github.com/fifi-run/atmospheric-gas-analysis)

Exploratory multivariate analysis of atmospheric gas measurements, with emphasis on data quality and unsupervised learning.

**Methods:** missing-data diagnostics, Multiple Imputation by Chained Equations (MICE) with predictive mean matching, principal component analysis (PCA), K-means and hierarchical clustering.

**Reported scope:** 183 observations and six columns. The coursework report selects three clusters and reports a K-means between-cluster sum-of-squares ratio of approximately 75.77%.

**Research note:** The source CSV is not included because its redistribution terms were not established. The report also contains inconsistent PCA variance statements; these are documented in the project README rather than silently reconciled.

### 3. Wine Quality Prediction

[Open project repository](https://github.com/fifi-run/wine-quality-prediction)

A supervised learning project using physicochemical measurements from the UCI Red Wine Quality dataset.

**Methods:** exploratory data analysis, outlier review, LASSO regression, Random Forest classification, cross-validation and feature-importance analysis.

**Dataset:** 1,599 observations and 11 physicochemical predictors.

**Research note:** Regression and classification metrics are treated as separate tasks. The raw dataset is not included; the repository provides the UCI citation and CC BY 4.0 attribution instructions.

### 4. Cancer Risk Assessment — Group 28

[Open project repository](https://github.com/fifi-run/cancer-risk-assessment)

A collaborative Introduction to Mathematics group project exploring a tabular lung-cancer risk-level dataset.

**Methods described in the group report:** multiclass logistic regression, Bayesian models and Random Forest. The supplied executable notebook contains a Random Forest classifier and a pruned Decision Tree workflow.

**Authorship:** Group 28 coursework. The repository does not claim sole authorship or assign individual contributions that are not documented in the source materials.

**Research note:** The dataset is not redistributed because its source and licence were not established. The project is an educational modelling exercise, not a clinical diagnostic system. The README distinguishes methods in the report from methods actually implemented in the notebook.

### 5. AI Ethics — Gender Bias in Artificial Intelligence

[Open project repository](https://github.com/fifi-run/ai-ethics-gender-bias)

A literature-based essay on the over-sexualisation of women in AI-generated imagery and the wider implications of gender bias in AI systems.

**Themes:** training-data representation, algorithmic discrimination, fairness interventions, privacy, social impact and institutional responsibility.

**Research note:** This is a critical writing sample, not an empirical modelling project. The project README summarises its argument without republishing third-party illustrative images from the original coursework PDF.

---

## Technical toolkit

**Programming and analysis:** R, Python, SQL  
**Statistical and machine learning methods:** regression, classification, random forests, regularisation, missing-data imputation, dimensionality reduction, clustering, model evaluation  
**AI and language technologies:** NLP, transformer-based model evaluation, deep learning concepts  
**Research practice:** experimental comparison, quantitative evaluation, data-quality assessment, methodological limitations and reproducibility documentation

The toolkit above reflects technologies and methods represented across the projects; it should not be read as a claim that every tool was used in every project.

## Data, reproducibility and academic integrity

- Each project is maintained separately so that its research question, methods, code and limitations can be reviewed independently.
- Data files are included only when their source and redistribution terms are sufficiently clear. Where they are not, the relevant README explains how to obtain an authorised copy.
- Reported metrics are identified as results from the supplied coursework reports or notebooks; they are not presented as independently reproduced results unless explicitly stated.
- Collaborative work is labelled as such. The Cancer Risk Assessment repository is identified as Group 28 coursework.
- Coursework reports and third-party figures are not republished where permission to redistribute has not been established.

## Repository directory

| Repository | Focus |
|---|---|
| [research-project](https://github.com/fifi-run/research-project) | MSc dissertation — human values in political discourse |
| [atmospheric-gas-analysis](https://github.com/fifi-run/atmospheric-gas-analysis) | Missing data, PCA and clustering |
| [wine-quality-prediction](https://github.com/fifi-run/wine-quality-prediction) | LASSO and Random Forest |
| [cancer-risk-assessment](https://github.com/fifi-run/cancer-risk-assessment) | Group modelling project |
| [ai-ethics-gender-bias](https://github.com/fifi-run/ai-ethics-gender-bias) | Literature-based AI ethics essay |

---

**Author:** Ziyi Wang  
**Academic background:** MSc Data Science, Durham University  
**GitHub:** [@fifi-run](https://github.com/fifi-run)
