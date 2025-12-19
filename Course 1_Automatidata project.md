# PACE Strategy Document

## 1. Plan Stage
**Q: What is the business task?**
* **Answer:** The goal is to develop a machine learning regression model to predict taxi cab fares in advance based on trip data (distance, time of day, etc.). This will help the NYC TLC improve user experience and operational efficiency.

**Q: Who are the stakeholders?**
* **Answer:**
    * **Internal (Automatidata):** Udo Bankole, Deshawn Washington, Luana Rodriquez, Uli King.
    * **External (NYC TLC):** Juliana Soto, Titus Nelson.

**Q: What are the initial requirements?**
* **Answer:** Create a global project document (Project Proposal), set up the Python environment, and acquire the NYC TLC dataset.

## 2. Analyze Stage
**Q: What data is required?**
* **Answer:** The NYC TLC dataset containing trip details (distance, time, fare amount, etc.) for over 200,000 licensees.

**Q: What specific analysis steps are needed?**
* **Answer:** Inspect data for duplicates and outliers (Data Cleaning), perform Exploratory Data Analysis (EDA) to understand variable distributions, and conduct A/B testing to investigate relationships between variables.

## 3. Construct Stage
**Q: What modeling techniques will be used?**
* **Answer:** We will use Multiple Linear Regression since the target variable (fare amount) is continuous. We will use Python packages like Pandas, NumPy, and Scikit-learn.

**Q: How will we evaluate the model?**
* **Answer:** We will test to ensure the model delivers consistent results and verify if it meets the initial project requirements before presenting to the client.

## 4. Execute Stage
**Q: What are the final deliverables?**
* **Answer:** A working regression model, visualizations of key insights for executives, and a final presentation summarizing the model's performance.


# Project Proposal: NYC TLC Trip Fare Prediction

**Document Status:** Draft
**Prepared By:** [Your Name], Data Analyst
**Client:** New York City Taxi and Limousine Commission (TLC)

## 1. Project Background
The New York City Taxi and Limousine Commission (TLC) has been collecting data on taxi and rideshare trips since 1971. The agency wants to modernize its approach by leveraging this data to improve rider experience. Specifically, they aim to provide riders with an estimated fare *before* the ride begins.

## 2. Project Goal
The primary goal is to build a **regression model** that predicts the fare amount for a taxi ride.
* **Target Variable:** Fare Amount ($)
* **Predictor Variables:** Trip distance, time of day, pickup/drop-off locations, and other relevant factors found in the dataset.

## 3. Scope & Deliverables
The Automatidata team will be responsible for the end-to-end data lifecycle, structured as follows:

| Milestone | Deliverable | Description |
| :--- | :--- | :--- |
| **1. Planning** | Project Proposal | Define goals, stakeholders, and timeline. |
| **2. Analysis** | EDA Report | Summary of data quality, cleaning steps, and initial visualizations. |
| **3. Construction** | Regression Model | A Python-based machine learning model to predict fares. |
| **4. Execution** | Executive Presentation | A deck containing insights, model performance metrics, and recommendations for TLC leadership. |

## 4. Methodology & Tools
* **Framework:** PACE (Plan, Analyze, Construct, Execute) 
* **Language:** Python
* **Key Techniques:**
    * Exploratory Data Analysis (EDA)
    * A/B Testing (to determine variable relationships)
    * Multiple Linear Regression

## 5. Stakeholders
* **Automatidata (Internal):**
    * Udo Bankole (Director) - *Requires confirmation of model requirements.*
    * Deshawn Washington (Manager) - *Project lead; requested Python & A/B testing.*
    * Luana Rodriquez (Snr Analyst) - *Lead on data inspection & EDA.*
    * Uli King (Snr PM) - *Client liaison.*
* **NYC TLC (Client):**
    * Juliana Soto (Finance)
    * Titus Nelson (Operations) - *Requires visual insights for executives.*

## 6. Assumptions & Risks
* **Assumption:** The provided dataset is representative of typical NYC traffic and pricing patterns.
* **Risk:** The dataset is large (200k licensees); efficient code will be necessary to handle processing time.


## Automatidata Project Proposal

<img width="894" height="580" alt="image" src="https://github.com/user-attachments/assets/af77e384-5ad2-401d-a244-f57c2e65b274" />

# Project Proposal: NYC TLC Taxi Fare Prediction

**Project Title:** New York City TLC Taxi Fare Prediction Model
**Status:** Draft

## Project Overview
The New York City Taxi and Limousine Commission (TLC) has partnered with Automatidata to develop a machine learning regression model. The primary objective is to predict the estimated fare amount for a taxi ride prior to the trip, based on historical trip data. This project will enable the TLC to improve rider transparency and operational efficiency.

## Project Tasks & Milestones

| Task Description | Milestone | PACE Stage | Relevant Stakeholder |
| :--- | :--- | :--- | :--- |
| **Draft Project Proposal** | Planning | Plan | Deshawn Washington |
| **Data Ingestion & Inspection** | EDA | Analyze | Luana Rodriquez |
| **Exploratory Data Analysis (EDA)** | EDA | Analyze | Luana Rodriquez |
| **A/B Testing** | Model Building | Analyze / Construct | Deshawn Washington |
| **Build Regression Model** | Model Building | Construct | Data Team |
| **Model Validation** | Model Building | Construct / Execute | Udo Bankole |
| **Create Visualizations** | Presentation | Execute | Titus Nelson |
| **Final Executive Presentation** | Presentation | Execute | Uli King |

---
---
# PACE Strategy Document: TikTok Claims Classification Project

## 1. Project Questions & Considerations

**Q: What is the business task?**
* **Answer:** The goal is to develop a machine learning model to classify video content as either a "claim" or an "opinion." This will assist TikTok moderators in processing user reports more efficiently and reducing the backlog.

**Q: Who are the stakeholders?**
* **Answer:**
    * **Data Team:** Willow Jaffey (Data Science Lead), Rosie Mae Bradshaw (Data Science Manager), Orion Rainier (Data Scientist).
    * **Cross-functional Team:** Mary Joanna Rodgers (Project Management Officer), Margery Adebowale (Finance Lead), Maika Abadi (Operations Lead).

**Q: What are the deliverables?**
* **Answer:**
    * A project proposal (Global document).
    * Exploratory Data Analysis (EDA) report.
    * A machine learning classification model.
    * Visualizations for executives.
    * Final presentation with key insights.

## 2. PACE Workflow (Classifying Tasks)

| Task Description | PACE Stage | Explanation |
| :--- | :--- | :--- |
| **Draft Project Proposal** | **Plan** | Involves defining scope, goals, and timeline before starting. |
| **Set up Python Environment** | **Plan** | Preparing the necessary tools for analysis. |
| **Inspect Data for Missing Values** | **Analyze** | Understanding the data quality is part of the analysis phase. |
| **Exploratory Data Analysis (EDA)** | **Analyze** | Investigating the data to find patterns and useful features. |
| **Determine Hypothesis Testing Method** | **Analyze** | Deciding how to statistically test the data relationships. |
| **Select Regression/Classification Model** | **Construct** | Choosing the right algorithm for building the model. |
| **Build Machine Learning Model** | **Construct** | The actual coding and training of the predictive model. |
| **Check Model Assumptions** | **Construct** | Verifying that the model works correctly and is unbiased. |
| **Generate Visuals for Executives** | **Execute** | Creating final outputs to communicate results. |
| **Present to Leadership Team** | **Execute** | Sharing the insights and solutions with stakeholders. |


## Project Proposal

<img width="807" height="599" alt="image" src="https://github.com/user-attachments/assets/e752fc7b-4b5f-494d-b813-0e54a2ff2a7c" />

# Project Proposal: TikTok Claims Classification

**Project Title:** Machine Learning Model for Claim vs. Opinion Classification
**Prepared By:** [Your Name], Data Analyst
**Status:** Draft

## Project Overview
TikTok’s Trust & Safety team is facing a challenge with the high volume of user reports on videos. Currently, moderators cannot review every video in a timely manner. The goal of this project is to develop a **machine learning model** that can reliably classify user interaction data as either a **"claim"** or an **"opinion."** This will allow for automated prioritization, reducing the backlog and improving the efficiency of the moderation process.

## Project Tasks & Milestones

The following table outlines the project workflow, aligning tasks with milestones, PACE stages, and relevant stakeholders.

| Order | Task Description | Milestone | PACE Stage(s) | Relevant Stakeholder |
| :--- | :--- | :--- | :--- | :--- |
| **1** | **Create Project Proposal** <br> *Draft a global document outlining deliverables and timeline.* | **Planning** | **Plan** | **Mary Joanna Rodgers** <br> *(PMO)* |
| **2** | **Set up Python Environment** <br> *Prepare the coding environment for the team.* | **Planning** | **Plan** | **Rosie Mae Bradshaw** <br> *(Manager)* |
| **3** | **Data Inspection** <br> *Check dataset for missing values and integrity.* | **Analysis** | **Analyze** | **Orion Rainier** <br> *(Data Scientist)* |
| **4** | **Exploratory Data Analysis (EDA)** <br> *Determine useful information within the data.* | **Analysis** | **Analyze** | **Orion Rainier** |
| **5** | **Determine Hypothesis Testing** <br> *Select the best method for statistical testing.* | **Analysis** | **Analyze** | **Willow Jaffey** <br> *(Data Science Lead)* |
| **6** | **Determine Model Type** <br> *Decide on the regression/classification model to use.* | **Model Building** | **Construct** | **Willow Jaffey** |
| **7** | **Build & Train Model** <br> *Develop the machine learning model.* | **Model Building** | **Construct** | **Data Team** |
| **8** | **Check Model Assumptions** <br> *Verify model reliability and bias.* | **Model Building** | **Construct** | **Rosie Mae Bradshaw** |
| **9** | **Generate Visualizations** <br> *Create visuals to share with TikTok executives.* | **Presentation** | **Execute** | **Mary Joanna Rodgers** |
| **10** | **Final Presentation** <br> *Present main talking points and model results to leadership.* | **Presentation** | **Execute** | **Willow Jaffey** |

## Key Stakeholders
* **Internal (Data Team):** Willow Jaffey, Rosie Mae Bradshaw, Orion Rainier.
* **Cross-functional:** Mary Joanna Rodgers, Margery Adebowale, Maika Abadi.

----
# Waze Project: User Churn Prediction

**Project Status:** Draft
**Prepared By:** [Your Name], Data Analyst
**Date:** [Current Date]

---

## Part 1: PACE Strategy Document

This document outlines the strategic workflow for the Waze User Churn project, utilizing the **PACE** (Plan, Analyze, Construct, Execute) framework.

### 1. Data Project Questions & Considerations

**Q: What is the business task?**
* **Answer:** The goal is to develop a machine learning model to predict **user churn** (users who stop using the app). By identifying at-risk users, Waze can improve retention strategies and grow the business.

**Q: Who are the stakeholders?**
* **Answer:**
    * **Data Team (Internal):** Harriet Hadzic (Director), May Santner (Manager/Supervisor), Chidi Ga (Senior Analyst), Sylvester Esperanza (Senior PM).
    * **Cross-functional Partners:** Emrick Larson (Finance), Ursula Sayo (Operations).

**Q: What are the deliverables?**
* **Answer:**
    1.  Project Proposal (Global project document).
    2.  Exploratory Data Analysis (EDA) Report.
    3.  Machine Learning Model (Churn Prediction).
    4.  Executive Visualizations & Presentation.

### 2. PACE Workflow (Task Classification)

The following tasks have been identified from leadership meetings. They are classified into the appropriate PACE stages:

| Task Description | PACE Stage | Explanation |
| :--- | :--- | :--- |
| **Draft Project Proposal** | **Plan** | Establishing goals, scope, and timeline before work begins. |
| **Set up Python Environment** | **Plan** | Preparing the technical tools required for the project. |
| **Inspect Dataset** | **Analyze** | Checking data integrity (missing values, duplicates) before deep analysis. |
| **Exploratory Data Analysis (EDA)** | **Analyze** | visualizing data to understand patterns and user behaviors. |
| **Conduct Hypothesis Testing** | **Analyze** | Statistically testing relationships between key variables (as suggested by May). |
| **Build Prediction Model** | **Construct** | Developing the machine learning algorithm to predict churn. |
| **Validate Model Results** | **Construct** | Testing the model for consistency and accuracy against requirements. |
| **Generate Visuals for Executives** | **Execute** | Creating easy-to-understand charts for non-technical stakeholders. |
| **Final Presentation** | **Execute** | Communicating insights and recommendations to leadership. |

---

## Part 2: Project Proposal

**Project Title:** Waze User Churn Prediction Model

### Project Overview
Waze leadership has identified **user churn** as a critical metric for business growth. Currently, there is a need to understand *who* is churning and *why*. The data team will develop a **machine learning model** 

[Image of machine learning classification]
 to predict users likely to uninstall or stop using the app. This will enable Waze to proactively engage at-risk users, thereby improving retention rates and optimizing product strategy.

### Project Tasks & Milestones

The following table aligns project tasks with milestones, PACE stages, and the requesting stakeholder based on initial meeting notes.

| Order | Task Description | Milestone | PACE Stage(s) | Relevant Stakeholder |
| :--- | :--- | :--- | :--- | :--- |
| **1** | **Create Project Proposal** <br> *Draft global document outlining goals and timeline.* | **Planning** | **Plan** | **Sylvester Esperanza** <br> *(Senior PM)* |
| **2** | **Set up Python Environment** <br> *Prepare coding environment for analysis.* | **Planning** | **Plan** | **May Santner** <br> *(Manager)* |
| **3** | **Data Inspection** <br> *Check for missing data, outliers, and integrity.* | **Analysis** | **Analyze** | **Chidi Ga** <br> *(Senior Analyst)* |
| **4** | **Exploratory Data Analysis (EDA)** <br> *Uncover patterns and relationships in user data.* | **Analysis** | **Analyze** | **Chidi Ga** |
| **5** | **Hypothesis Testing** <br> *Test relationships between key variables.* | **Analysis** | **Analyze** | **May Santner** |
| **6** | **Build Machine Learning Model** <br> *Develop model to predict monthly user churn.* | **Model Building** | **Construct** | **Data Team** |
| **7** | **Model Validation** <br> *Ensure model meets project requirements and consistency.* | **Model Building** | **Construct** | **Harriet Hadzic** <br> *(Director)* |
| **8** | **Generate Visualizations** <br> *Create visuals for executive sharing.* | **Presentation** | **Execute** | **Sylvester Esperanza** |
| **9** | **Final Presentation** <br> *Define main talking points and present to leadership.* | **Presentation** | **Execute** | **Harriet Hadzic** |

### Key Takeaways for Success
* **Communication:** Adjust technical language when speaking with cross-functional partners (Emrick & Ursula).
* **Tools:** Python will be the primary tool for this project.
* **Focus:** The project specifically targets *monthly* user churn.



[Strategy Document](https://docs.google.com/document/d/1RaTEjQY1qFWOhNAK7n3lyUoXX9E8lRJ9JatRp05sNG4/template/preview?resourcekey=0-kFO66RukJ-dtCmD-QvJc3w)

[Project Proposal](https://docs.google.com/document/d/1Teq5Y1sEBbf_kULYYlUq6-WC1G8f90bYoyQtIHVvJXg/template/preview)  
