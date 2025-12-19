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
