# Housing Prices — Statistical Analysis Project

## Project overview
This project is an **academic learning project** developed as part of my **postgraduate studies in Data Science (Level 9 degree)** with a strong focus on **Statistics, Probability, Regression Analysis, Machine Learning, and AI**.

The goal of the project is to demonstrate **statistical reasoning and understanding**, not only technical implementation. Exploratory Data Analysis (EDA) is used as the **starting point**, followed by probability-based analysis, statistical inference, and regression modeling.

The dataset is taken from the Kaggle competition **“House Prices: Advanced Regression Techniques”**, which contains detailed information about residential properties and their sale prices.

---

## Project objectives
- Develop a solid statistical understanding of a real-world dataset
- Use **EDA** as a foundation for further statistical analysisS
- Analyze **probability distributions** of key variables
- Apply **statistical inference** and hypothesis testing
- Build and interpret **linear regression models** as statistical tools
- Connect classical statistics with machine learning concepts

The emphasis of this project is on **interpretability, assumptions, and uncertainty**, rather than predictive performance.

---

## Dataset summaryS
- **Number of observations:** 1460 houses
- **Number of features:** 81 variables
- **Target variable:** `SalePrice`

The dataset includes information about:
- house size and layout
- quality of materials and finish
- neighborhood and location
- additional features such as garages, fireplaces, pools, and fences

A full description of variables is provided in `data_description.txt`.

---

## Project structure

ADD IMAGE OF STRUGTURE PROJECT

---

## Stage 1 — Exploratory Data Analysis (EDA)
EDA is used as the **first step** to understand the structure, quality, and limitations of the data.

### Completed steps
- Loaded the dataset and inspected its dimensions (**1460 rows, 81 columns**)
- Reviewed data types using `df.info()`
- Identified numerical and categorical variables
- Analyzed missing values and distinguished between:
  - **structural missing values** (absence of a feature, e.g. no pool or no fence)
  - **missing measurements**
- Examined the distribution of `OverallQual`
  - Most houses have average quality (values 5–7)
- Studied the relationship between `OverallQual` and `SalePrice`
  - Median sale price increases monotonically with higher quality
- Visualized price distributions by quality using boxplots
  - Observed increasing spread and presence of outliers at higher quality levels

EDA is treated as an **analytical foundation**, not as an end goal.

---

## Stage 2 — Distributions and Probability

In this stage, I focus on **understanding how the data is distributed** before applying statistical tests or regression models.

Before using any statistical methods, it is important to first look at the data and understand its basic shape. House prices are not evenly distributed, and this can affect the choice of statistical methods later in the project.

### What I do in this stage:
- Look at the distribution of house prices (`SalePrice`)
- Check whether the distribution is symmetric or skewed
- Understand why house prices are not normally distributed
- Apply a log transformation to `SalePrice`
- Compare the distribution before and after the transformation
- Learn why these steps are important for later hypothesis testing and regression analysis

The goal of this stage is not to build models, but to **prepare the data and improve my understanding** before moving on to statistical tests and linear regression.

---

## Stage 3 — Statistical Inference (planned)
This stage introduces **formal statistical reasoning and uncertainty**.

Planned analyses:
- Formulate statistical hypotheses related to house prices
- Compare groups (e.g. houses with vs without a garage)
- Use confidence intervals to quantify uncertainty
- Apply hypothesis testing and interpret p-values carefully
- Emphasize interpretation over mechanical testing

---

## Stage 4 — Linear Regression Analysis (planned)
Linear regression is used here primarily as a **statistical model**, not only as a predictive tool.

Planned analyses:
- Simple linear regression (e.g. price vs quality, price vs size)
- Interpretation of regression coefficients
- Confidence intervals for coefficients
- Multiple linear regression with selected predictors
- Discussion of multicollinearity and omitted variable bias

---

## Stage 5 — Regression Diagnostics and Assumptions (planned)
This stage focuses on **model validity and assumptions**, which is essential at postgraduate level.

Planned analyses:
- Residual analysis
- Linearity and non-linearity
- Homoscedasticity and heteroscedasticity
- Normality of residuals
- Influence of outliers and leverage points

---

## Connection to Machine Learning
After establishing a strong statistical foundation, regression models will be connected to machine learning concepts such as:
- regularization
- bias–variance trade-off
- comparison between statistical and ML perspectives

---

## Academic context
This project is part of my **postgraduate training in Data Science (Level 9)**. The primary objective is to demonstrate:
- statistical thinking
- methodological rigor
- clear interpretation of results
- reproducible and well-documented analysis

The project evolves gradually as new statistical and machine learning concepts are introduced during the program.
