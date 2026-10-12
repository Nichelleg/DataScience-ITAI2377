# Data Science in AI | ITAI 2377

**Nichelle Graf**  
Bachelor of Applied Technology — Applied AI & Robotics  
Houston City College | Fall 2026  
**Instructor:** Professor Karthik Rajan  
**Course Status:** In Progress

---

## About This Repository

This repository documents my coursework, technical assignments, and collaborative projects for ITAI 2377: Data Science in AI at Houston City College.

The course explores how data can be collected, prepared, analyzed, and interpreted to support informed decisions and develop reliable AI systems.

My particular interest is in connecting technical analysis with practical applications, including business operations, financial analysis, intelligent automation, and AI system evaluation.

This repository serves two purposes:

- **Academic Record:** Documentation of coursework, technical exercises, projects, and learning experiences.
- **Professional Portfolio:** Selected work demonstrating analytical thinking, technical problem-solving, data validation, and the practical application of AI technologies.

---

## Technical Skills & Tools

### Programming & Development
- Python
- Jupyter Notebook / Google Colab
- Visual Studio Code
- Git and GitHub

### Data Analysis & Processing
- Pandas and NumPy
- Data collection and preprocessing
- Exploratory data analysis (EDA)
- Dataset validation and alignment
- Data visualization
- Descriptive statistics
- Time-series preprocessing

### Statistical Analysis
- Linear regression
- Correlation and coefficient of determination (R²)
- Comparative statistical analysis
- Scatterplots and trendlines
- Risk assessment and interpretation
- Statistical model evaluation

### Machine Learning & AI
- Scikit-learn
- Natural language processing (NLP)
- Text preprocessing and tokenization
- GloVe word embeddings
- BERT contextual embeddings
- Cosine similarity analysis
- Data preparation for sequential models
- Data leakage prevention

### Visualization & Documentation
- Matplotlib
- Seaborn
- Microsoft Excel
- Microsoft Word
- PowerPoint
- Technical reports and presentations

---

## Coursework & Group Projects

The following projects were completed collaboratively as part of Team Insight.

| Assignment | Project | Technical Focus | Status |
|------------|---------|-----------------|--------|
| Group Lab 02 | Data Science Panel Presentation | Machine learning, deep learning, preprocessing, feature scaling, embeddings, and data leakage | Completed |
| Group Lab 03 | The XLE Recovery Play | Financial data analysis, regression, investment evaluation, and risk assessment | Completed |
| Group Lab 04 | ReversePsychology AI — NVIDIA Time-Series Preprocessing | Time-series gaps, forward filling, chronological data preparation, and look-ahead leakage | Completed |
| Group Lab 05 | Data Preprocessing for Generative AI | Text preprocessing, GloVe, BERT, cosine similarity, statistical comparison, and validation | Completed |
| Midterm | Data Science Midterm Project | Documentation pending | To be updated |

*Project reports, notebooks, presentations, and supporting materials will be added as they are organized.*

---

# Featured Projects

## Group Lab 03: The XLE Recovery Play

**Project:** Drawing Insights from Data to Make Money Decisions  
**Status:** Completed  
**Team:** Crystal Insight

### Project Overview

Developed an evidence-based investment proposal examining potential recovery opportunities following the historic collapse in crude oil prices during the COVID-19 pandemic.

The objective was to identify an investment that could benefit from an eventual energy-sector recovery while considering statistical relationships, company-specific risks, and investment uncertainty.

### Data & Methodology

Our team:

- Analyzed 815 matched trading days from January 2017 through April 2020.
- Collected WTI crude oil prices using EIA/FRED data.
- Retrieved historical investment prices from Nasdaq.
- Evaluated five investment candidates: Boeing (BA), Occidental Petroleum (OXY), ConocoPhillips (COP), Frontline (FRO), and the Energy Select Sector SPDR Fund (XLE).
- Aligned commodity and equity datasets by calendar date.
- Applied linear regression to evaluate relationships between oil prices and investment prices.
- Compared overall regression results with pre-pandemic market behavior.
- Considered company-specific and sector-wide investment risks.

### Key Findings

ConocoPhillips demonstrated the strongest overall regression relationship with crude oil prices (R² ≈ 0.69).

However, XLE showed a stronger relationship during the relatively stable 2019 period and provided diversification across multiple energy companies.

Our team recommended a modest investment in XLE rather than concentrating the Family Fund in a single company.

### Skills Demonstrated

- Financial data procurement
- Dataset alignment and preprocessing
- Linear regression and R² interpretation
- Comparative statistical analysis
- Data visualization
- Risk evaluation
- Avoiding look-ahead bias
- Translating analytical findings into practical recommendations

### Key Takeaway

A strong statistical relationship does not automatically justify an investment decision.

Effective data science requires understanding the business context, evaluating risk, questioning assumptions, and recognizing the limitations of statistical models.

**Deliverables:** Technical report, Excel regression workbook, and group presentation.

---

## Group Lab 04: ReversePsychology AI — NVIDIA Time-Series Preprocessing

**Project:** Designing a Beginner Data Science Lab  
**Status:** Completed  
**Team:** Team Insight

### Project Overview

Designed and tested an instructional data science lab for a fictional AI education company, ReversePsychology AI.

The project used historical NVIDIA (NVDA) stock data to teach beginning students how to identify structural gaps in financial time-series data and prepare a continuous calendar-based dataset without introducing future information.

### Technical Implementation

The student lab demonstrated:

- Importing and examining historical NVIDIA stock data.
- Identifying weekends and market holidays as structural gaps.
- Creating a continuous daily calendar.
- Distinguishing observed trading days from inserted dates.
- Using forward fill (`ffill`) to populate missing values.
- Preserving an `observed_day` indicator.
- Visualizing original and processed time-series data.
- Preparing data for a potential LSTM application.
- Explaining chronological train/test splitting and look-ahead leakage.

### My Contributions

My individual work focused on technical validation, instructional design, and project coordination.

I:

- Helped restructure the project documentation to distinguish the team's assignment from the student-facing lab.
- Reviewed the public dataset and identified inconsistencies between the original notebook and the required CSV dataset.
- Helped standardize the notebook around a reproducible public dataset.
- Revised instructions, code comments, checkpoints, and explanatory sections.
- Tested the lab from the perspective of a beginner student.
- Helped coordinate shared documentation, revisions, and final deliverables.

### Key Takeaway

Designing an instructional lab requires more than writing technically correct code.

An effective learning experience must also provide accessible data, clear instructions, reproducible results, and explanations that connect each technical step to its purpose.

**Deliverables:** Lab design report, student notebook, and group presentation.

---

## Group Lab 05: Data Preprocessing for Generative AI

**Status:** Completed  
**Team:** Team Insight

### Project Overview

Explored text preprocessing and semantic representation using the BBC News dataset containing 2,225 articles across five categories.

The project compared traditional GloVe word embeddings with contextual BERT embeddings using cosine similarity, statistical analysis, and data visualization.

The objective was to understand how preprocessing and representation choices influence the quality and interpretation of data used in AI applications.

### Technical Implementation

The lab included:

- Exploring the BBC News dataset.
- Text cleaning and normalization.
- Tokenization and stop-word removal.
- Lemmatization.
- Generating GloVe embeddings.
- Generating BERT embeddings.
- Calculating cosine similarity matrices.
- Comparing same-category and different-category article similarities.
- Statistical analysis and visualization.
- Evaluating category separation.

### Key Findings

Our final experiment produced the following results:

| Metric | GloVe | BERT |
|--------|-------|------|
| Same-category similarity | 0.9798 | 0.7781 |
| Different-category similarity | 0.9618 | 0.7118 |
| Category separation score | 0.0179 | 0.0663 |

BERT demonstrated greater separation between same-category and different-category articles in this experiment.

These findings do not establish that BERT is universally superior, but they illustrate how contextual embeddings can capture distinctions that differ from those represented by static word embeddings.

### My Contributions

My primary contribution involved independently reviewing and validating the notebook's implementation and analytical results.

During this process, I:

- Identified an unrepresentative sampling method that selected only business articles.
- Implemented balanced sampling of 20 articles from each of five categories.
- Discovered an incorrectly indented `else` statement that produced misleading similarity results without generating a Python error.
- Independently verified calculations across notebook sections.
- Investigated inconsistent outputs between notebook executions.
- Restarted the runtime and confirmed reproducible results through a complete execution.

### Key Takeaway

Code that executes without errors does not necessarily produce correct analytical results.

Reliable data science requires validating assumptions, independently checking calculations, and confirming that results are reproducible.

This project reinforced the distinction between verification, validation, and reproducibility.

**Deliverables:** Completed notebook documentation and team reflection journal.

---

## Group Lab 02: Data Science Panel Presentation

**Status:** Completed  
**Format:** Collaborative panel presentation

### Project Overview

Participated in a group presentation examining fundamental concepts in machine learning and deep learning.

The presentation addressed seven questions involving:

- Differences between machine learning and deep learning.
- When deep learning is an appropriate choice.
- The importance of preprocessing.
- Normalization versus standardization.
- High-cardinality categorical data and embeddings.
- Data augmentation versus duplication.
- Data leakage and chronological data splitting.

The project emphasized communicating technical concepts clearly to an audience rather than relying solely on code or mathematical explanations.

### Skills Demonstrated

- Technical communication
- Collaborative presentation
- Explaining machine learning concepts
- Data preprocessing principles
- Model evaluation considerations

**Deliverable:** Group PowerPoint presentation.

---

## Data Science Midterm

**Status:** Documentation pending

Midterm project documentation and supporting materials will be added after review.

---

## Learning Objectives

Through this course, I am developing the ability to:

1. Collect, clean, and organize data from multiple sources.
2. Perform exploratory data analysis and statistical evaluation.
3. Apply regression and other analytical techniques to practical problems.
4. Prepare time-series data while avoiding future-information leakage.
5. Implement and compare text preprocessing and embedding techniques.
6. Evaluate analytical results through independent verification.
7. Communicate data-driven findings to technical and nontechnical audiences.
8. Recognize the importance of data quality, reproducibility, and responsible AI development.

---

## Professional Applications

My professional interests include applying data science to:

- Real estate market analysis
- Business intelligence
- Operational analytics and optimization
- Financial and investment analysis
- Enterprise data systems
- Intelligent automation
- AI system evaluation and governance

My background in real estate and property management has reinforced the importance of using detailed, reliable data to support decisions.

I am particularly interested in understanding how data quality, preprocessing decisions, and model evaluation affect the reliability of AI systems operating in real-world environments.

---

## Professional Development & Reflection

A recurring theme throughout my Data Science coursework has been the importance of examining analytical processes rather than simply accepting their outputs.

Across multiple projects, I have worked on:

- Identifying inconsistencies in source data.
- Reconciling datasets and technical documentation.
- Testing analytical workflows.
- Independently verifying calculations.
- Improving reproducibility.
- Translating technical findings into understandable conclusions.

These experiences have reinforced my interest in data quality, AI evaluation, and developing systems that produce reliable, meaningful results.

---

## Portfolio Navigation

**Main AI & Robotics Portfolio:**  
[AI-Portfolio-Nichelle-Graf](https://github.com/Nichelleg/AI-Portfolio-Nichelle-Graf)

### Related Coursework

- [Computer Vision](https://github.com/Nichelleg/ComputerVision-ITAI1378)
- [Deep Learning](https://github.com/Nichelleg/DeepLearning-ITAI2376)
- [Natural Language Processing](https://github.com/Nichelleg/NLP-ITAI2373)
- [AI Applications & Case Studies](https://github.com/Nichelleg/AI-Apps-ITAI2372)

---

## Collaboration & Attribution

The group projects documented in this repository were completed collaboratively as part of ITAI 2377.

Project descriptions distinguish shared team outcomes from my individually documented contributions where applicable.

Original reports and presentations identify participating team members.

---

*This repository is maintained as part of my ongoing studies in Applied Artificial Intelligence & Robotics at Houston City College.*
