# AITECH Student Satisfaction Survey Project (2023, January - July)  

---

## Table of Contents
1. [Project Overview](#project-overview)  
2. [Methodology & Statistical Techniques](#methodology--statistical-techniques)  
3. [Data Analysis & Key Findings](#data-analysis--key-findings)  
4. [Interpretations & Strategic Insights](#interpretations--strategic-insights)  
5. [Conclusion & Reflections](#conclusion--reflections)

---

## Project Overview

This project began with a clear goal, to assess how satisfied students at AITECH were with their learning environment, instruction quality, and related academic services. The dataset covered a small but diverse student sample (n=42), capturing variables such as:

- Program enrolled  
- Learning environment  
- Instruction clarity  
- Materials & support availability  
- Duration of enrollment  
- How students heard about AITECH

### My Thought Process

I approached this project with both curiosity and structure. I wanted to:
- Understand general satisfaction levels using **descriptive stats**  
- Test hypotheses around program differences using **T-Tests** and **ANOVA**  
- Assess associations and relationships using **Chi-square**, **Correlation**, and **Crosstabulation**  

At one point, I accidentally recoded the unique ID as a string (a rookie mistake 😅), which caused display issues in SPSS. That forced me to re-import and re-label variables carefully, a valuable reminder to respect data types early on.

---

## Methodology & Statistical Techniques

I followed a stepwise approach:

1. **Data Preparation**  
   - Imported and relabeled variables in SPSS  
   - Checked for duplicates and standardized measures  
   - Recoded categorical variables for clarity

2. **Statistical Analyses Performed**
   - **Descriptive Statistics**: Means, skewness, kurtosis  
   - **Independent Samples T-Test**: Program-wise learning environment comparison  
   - **One-Way ANOVA**: Instruction quality vs. enrollment duration  
   - **Chi-Square Test**: Referral channel vs. enrolled program  
   - **Correlation Analysis**: Instruction quality vs. perceived learning environment  
   - **Crosstabulation + Chi-Square**: Program duration vs. program enrolled

---

## Data Analysis & Key Findings

### 1. Descriptive Statistics

- Mean scores ranged from **1.86 to 2.38**, indicating generally **positive student sentiment**  
- Most **skewness values ~0**, responses are relatively symmetric  
- Some **kurtosis values >3**, indicating possible outliers  
- Standard deviations were low, suggesting **high agreement** among responses

---

### 2. Independent Samples T-Test  
**Question:** Do students in Cybersecurity and Data Analysis experience the learning environment differently?

- **p-value:** 0.750 (> 0.05)  
- No significant difference. The learning environment experience is consistent across programs.

---

### 3. One-Way ANOVA  
**Question:** Does the quality of instruction differ based on enrollment duration?

- **p-value:** 0.963 (> 0.05)  
- No significant variation. Perceptions of instructional quality remain consistent across enrollment length.

---

### 4. Chi-Square Test  
**Question:** Is there a link between how students heard about AITECH and what program they chose?

- **p-value:** 0.001  
- Significant association. For example, Instagram brought more students than expected to specific programs.

---

### 5. Correlation Analysis  
**Question:** Are instruction quality and perceived learning environment connected?

- **r = 0.568**, **p-value = 0.001**  
- Moderate positive correlation. Better instruction correlates with more positive perceptions of the learning environment.

---

### 6. Crosstabulation  
**Question:** Does enrollment duration affect the program a student picks?

- **p-value:** 0.010  
- Statistically significant. Students’ enrollment durations seem to influence the program they select.

---

## Interpretations & Strategic Insights

- **Learning Environment**: Universally positive across programs, with no biases  
- **Instruction Quality**: Perceived uniformly across different durations  
- **Marketing Channel Effectiveness**: Instagram is a **key referral source**, a channel to scale  
- **Instruction & Environment Link**: Strong correlation signals that **investing in teaching** boosts overall satisfaction  
- **Program Choice Influenced by Duration**: Shorter vs longer-term commitment patterns may guide curriculum marketing strategies

---

## Conclusion & Reflections

This project revealed several important insights, despite the dataset’s small size. It emphasized the power of **basic inferential stats** in helping schools like AITECH:
- Make **data-driven decisions**  
- Understand student experience patterns  
- Refine program offerings and marketing strategies  

### Reflections

Working in SPSS was a great way to reinforce my statistical fundamentals:
- From managing data types to avoiding recode errors  
- From navigating output interpretation to translating numbers into strategy  
- From technical hypothesis testing to **real-world education planning**

This project reminded me that even **simple data**, if explored right, can spark **big decisions**.

---

Thanks for reading!  
**Author:** Kingsley Sase  
**GitHub:** [@Kingsleysase](https://github.com/Kingsleysase)
