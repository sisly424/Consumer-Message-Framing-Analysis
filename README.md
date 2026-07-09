# Consumer Message Framing Analysis

An experimental marketing analytics project investigating how different product messages influence consumer perception and purchase behavior.

Using a randomized between-subjects experiment, this project evaluates whether emphasizing **sustainability** or **durability** leads to different consumer responses. Statistical analyses were conducted using Python and R to identify both overall effects and demographic differences, providing actionable recommendations for marketing communication strategies.

---

## Project Overview

Marketing campaigns often promote different aspects of the same product. For products with both functional and sustainable attributes, marketers face an important question:

> Should advertising emphasize product durability or environmental sustainability?

This project applies experimental design and causal inference methods to evaluate how different message framing strategies influence consumer perception, purchase intention, and recommendation likelihood.

Rather than relying on observational data, a randomized experiment was conducted to estimate the causal impact of message framing on consumer behavior.

---

## Business Problem

As sustainability becomes increasingly important in consumer marketing, companies invest significant resources in environmentally focused messaging. However, sustainability messaging may not be equally effective across all customer segments.

The objective of this study is to identify:

- Whether sustainability messaging improves consumer responses
- Which customer segments are most responsive
- How demographic characteristics influence marketing effectiveness
- How marketers can better target advertising campaigns

---

## Research Questions

This project investigates the following questions:

- Does sustainability framing improve perceived product performance?
- Does message framing influence purchase intention?
- Does message framing increase recommendation likelihood?
- Does environmental concern moderate framing effectiveness?
- Do demographic characteristics influence consumer responses?

---

## Experimental Design

**Study Design**

Randomized Between-Subjects Experiment

**Sample Size**

302 participants

**Survey Platform**

Qualtrics

Participants were randomly assigned to one of two advertising conditions.

**Condition A**

Durability-focused message

> "Built to last, not to crack."

**Condition B**

Sustainability-focused message

> "Built to refill, not to replace."

Participants then evaluated the product using Likert-scale survey questions measuring consumer attitudes and behavioral intentions.

---

## Variables

### Independent Variable

- Message Framing
    - Durability
    - Sustainability

### Dependent Variables

- Perceived Product Performance
- Purchase Intention
- Recommendation Likelihood

### Moderators

- Environmental Concern
- Gender
- Age Group

---

## Tools & Technologies

- Python
- R
- Jupyter Notebook
- Pandas
- Qualtrics
- Experimental Design
- Causal Inference
- Statistical Inference
- Data Visualization

---

## Statistical Methods

The following analyses were conducted:

- Independent Samples T-test
- Two-way ANOVA
- Three-way ANOVA
- Effect Size Analysis
- Statistical Power Analysis

---

## Key Findings

### Sustainability Improves Product Perception

Participants exposed to sustainability-focused messaging reported significantly higher perceived product performance than those exposed to durability-focused messaging.

---

### Purchase Intention Was Not Significantly Different

Although sustainability framing improved product perception, no statistically significant difference was observed in overall purchase intention or recommendation likelihood.

---

### Environmental Concern Moderates Message Effectiveness

Consumers with stronger environmental concern responded significantly better to sustainability messaging.

This finding suggests that advertising effectiveness depends on consumer values rather than message content alone.

---

### Demographic Differences Matter

The impact of sustainability messaging varied across demographic groups.

Significant interaction effects were observed across combinations of:

- Age
- Gender
- Environmental concern

These results indicate that message framing should be tailored for different customer segments instead of applying a single communication strategy.

---

## Business Recommendations

Based on the experimental results, marketers should:

- Prioritize sustainability messaging when targeting environmentally conscious consumers.
- Personalize advertising strategies according to demographic characteristics.
- Consider regional and audience-specific values when designing campaigns.
- Combine sustainability and functional product benefits for broader market appeal.

---

## Repository Structure

```
consumer-message-framing-analysis
│
├── Code.ipynb
├── Experiments & Causal Inference Report.pdf
├── Experiments & Causal Inference Presentation.pdf
├── MBAN+Grp+14-19_datafile_value.csv
├── survey_Dura.csv
├── survey_Sust.csv
├── survey_map.html
└── README.md
```

---

## Repository Contents

| File | Description |
|------|-------------|
| Code.ipynb | Data cleaning, statistical analysis, and visualization workflow |
| Experiments & Causal Inference Report.pdf | Full project report describing methodology, statistical analyses, and conclusions |
| Experiments & Causal Inference Presentation.pdf | Project presentation summarizing the research findings |
| MBAN+Grp+14-19_datafile_value.csv | Processed dataset used for statistical analysis |
| survey_Dura.csv | Survey responses from the durability message condition |
| survey_Sust.csv | Survey responses from the sustainability message condition |
| survey_map.html | Interactive visualization of participant geographic distribution |

---

## Future Improvements

Potential extensions of this project include:

- Increasing sample size to improve statistical power
- Evaluating additional product categories
- Comparing combined durability and sustainability messaging
- Incorporating additional demographic and behavioral variables
- Testing longitudinal effects on consumer behavior

---

## Team

Group 18

Master of Business Analytics

UBC Sauder School of Business

- Sisly Lyu
- Candice Miao
- Romee Sun
- Xiaoxi Xu
- Michael Ruizhe Zhang

---

## Skills Demonstrated

- Experimental Design
- Causal Inference
- Marketing Analytics
- Consumer Behavior Analysis
- Survey Design
- Hypothesis Testing
- A/B Testing
- T-test
- ANOVA
- Statistical Inference
- Python
- R
- Data Visualization
