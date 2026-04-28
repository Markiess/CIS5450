# Final Project: Detailed Rubric

## CIS 5450: Big Data Analytics

### Types of Scoring Labels

- ➕ **Positive scoring (select multiple):** the section starts with 0, points stack if multiple aspects of the rubric are met.
- ✖️ **Negative scoring (select 1):** the section starts with the max points available for each section, and points are deducted if elements are missing from each section.
- ✖️✖️ **Negative scoring (select multiple):** the section starts with the max points available, and points stack if multiple aspects of the rubric are missing.

---

## 1. Project Proposal (+5 points) ✖️


| Condition                                                                                                                                                            | Penalty |
| -------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------- |
| All Good: Project Proposal submitted on time                                                                                                                         | -0      |
| Late Submission: Project Proposal submitted late                                                                                                                     | -5      |
| Failure to add all team members: Every time you re-submit, you need to re-add your teammate. Failure to do so will result in a 5 points penalty for the entire team. | -5      |


---

## 2. Intermediate Check-In (+5 points) ✖️✖️

**Check-In Questions:**

- **Get to know your data:** Have you recognized issues / assumptions with your data and how do you plan to handle them?
- **EDA:** Do you have at least 3 meaningful EDA visuals?
- **Modeling:** How does the baseline model perform? Comment on the performance. What are the 2-3 models that you will further implement? Why have you chosen these models over other options?
- **Project Management:** What's the plan of action? By when do you plan to complete various stages of this project?
- **Hypothesis Testing:** If you plan on incorporating hypothesis testing, what are 2-3 of your potential hypotheses based on the data? How do you plan to test these hypotheses?


| Condition                                                                                                                                                                                                                                                         | Penalty        |
| ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------- |
| All Good: intermediate check-in completed on time with sufficient and clear responses to the above questions.                                                                                                                                                     | -0             |
| Insufficient work completed: intermediate check-in completed on time, but insufficient work completed or responses to the questions above (incomplete EDA or missing baseline model). One point deduction for insufficient answer to each of the questions above. | -1 (stackable) |
| No work completed: Notebook not created, no data loaded, insufficient responses for all questions above.                                                                                                                                                          | -5             |
| Late: intermediate check-in not completed on time                                                                                                                                                                                                                 | -5             |
| Individual Penalty: Team Members did not show up or show up very late without valid reason.                                                                                                                                                                       | -5             |


---

## 3. Difficulty (+13 points) ➕

Points will be awarded on the **depth** of application of these topics. Award partial credit if the usage of the feature is not fully justified OR if the feature is not well implemented. If there are more than 3 concepts used, choose the **best 3 concepts**. We prioritize **depth** (applying the concepts well) rather than **breadth** (touching on many concepts).

**Eligible Concepts:**

- **Feature importance:** using feature importance method in tree models OR using coefficient in regression model to identify most important features
- **Feature selection:** explore using forward/backward feature selection, PCA, regularization to narrow down feature space
- **Other visualization packages:** using plotly, folium
- **Feature engineering:** use of other categorical encoding methods or engineering interaction terms to help improve model performance
- **Ensemble models:** implementing ensemble models
- **Imbalance data:** using upsampling/downsampling/SMOTE-derivative methods when dealing with an imbalanced data set
- **Hyperparameter tuning:** using smarter hyperparameter tuning methods such as Randomized Search or Bayesian Optimization
- **Hypothesis Testing:** using simulation-based hypothesis testing and statistical analysis to test interpret models and test claims about model validity
- **Entity Linking:** using entity linking to enrich data sets and/or combine data sets that are not obviously compatible

> Additionally, you will be asked to fill out an additional notebook template where you will identify where you used each difficulty concept.

**Scoring per concept (×3 concepts):**


| Criterion                                        | Points |
| ------------------------------------------------ | ------ |
| Concept is implemented correctly                 | +1     |
| Use of concept is fully justified                | +1     |
| Results are used and reflected in the conclusion | +1     |
| Correctly identify where concept is used         | +1     |
| **Concept Total**                                | **+4** |



| Bonus                                                                                   | Points |
| --------------------------------------------------------------------------------------- | ------ |
| Team went above and beyond on one of the concept implementations                        | +1     |
| Standard Project: this project follows the standard outline/difficulty of our homeworks | +0     |


---

## 4a. EDA (+10 points) ✖️

EDA steps may include (but are not limited to) the following:

- ☑️ Provide necessary context on attributes in relation to overall dataset.
- ☑️ Provide background on the issue statement and high-level definitions of critical variables
- ☑️ Understand key variables' data types, summary statistics, and distribution (using histogram/scatter plot/pair-plots)
- ☑️ Identify outliers and understand how it may be handled

Each step should include a brief summary of findings in a markdown cell, and inform the roadmap for the project as a whole.


| Grade     | Description                                                                                                                                                                                                                                                                     | Penalty |
| --------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------- |
| Excellent | Incorporated all necessary EDA aspects proficiently with each step providing a further understanding of the underlying data. EDA is informative and succinct (quality over quantity). Furthermore, EDA is used to tell a story based on business sense and/or domain knowledge. | -0      |
| Good      | Incorporated all necessary EDA aspects proficiently with each step providing a further understanding of the underlying data.                                                                                                                                                    | -3      |
| Average   | Incorporated most necessary EDA aspects proficiently. Some EDA steps may not fit in the larger scope of the project. Most steps come with justification.                                                                                                                        | -5      |
| Fair      | Incorporated a few EDA aspects proficiently. Many EDA steps are performed without justifications and detract from the overall objective.                                                                                                                                        | -8      |
| Poor      | Simply imported data without any EDA                                                                                                                                                                                                                                            | -10     |


---

## 4b. Data Pre-processing & Feature Engineering (+10 points) ✖️✖️

Feature engineering / data pre-processing steps may include (but are not limited to) the following:

- ☑️ Handle null values appropriately based on variable distribution
- ☑️ Handle outliers appropriately
- ☑️ Engineer appropriate new features
- ☑️ One-hot encode categorical variable (if applicable)
- ☑️ Check variable correlation/remove highly correlated variables
- ☑️ Address imbalanced data
- ☑️ Scale data


| Grade     | Description                                                                                                                                                                                             | Penalty |
| --------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------- |
| Excellent | Incorporated all necessary aspects proficiently with sufficient justification for choices. Feature engineering and data pre-processing steps are informed decisions following insights drawn from EDA.  | -0      |
| Good      | Incorporated most necessary aspects proficiently with sufficient justification for choices. Feature engineering and data pre-processing steps are informed decisions following insights drawn from EDA. | -3      |
| Average   | Incorporated a few necessary aspects with lack of justification for choices                                                                                                                             | -5      |
| Poor      | Incorporated a few necessary aspects with lack of justification for choices and conceptual errors were made                                                                                             | -8      |
| None      | The group simply loaded the data and proceeded to modeling.                                                                                                                                             | -10     |


---

## 5a. Model Implementation (+12 points) ✖️✖️

**Example Justification Errors (but not limited to these):**

- ➡️ Failing to address model limitations and potential biases when choosing model
- ➡️ Introduce new model but it has the same potential shortcomings of the original model
- ➡️ Use NN models when the goal is having an interpretable/explainable results

**Example Conceptual Errors (but not limited to these):**

- ➡️ Increased regularization for already underfit models
- ➡️ Increased complexity for already overfit models

**Pipeline** (if any is applicable, -1 point for each incorrect implementation, up to 5 points):

- Failure to train-test-split data
- Applied `.fit` on test data for either standardization, PCA, or modeling
- Applied standardization/PCA before train-test split
- Applied up/downsampling before train-test split
- Impute missing values based on statistics (mean, median, mode) calculated from the entire dataset
- Incorporate test set for hyper-parameter tuning (instead of using validation set)


| Section                                                                                   | Penalty           |
| ----------------------------------------------------------------------------------------- | ----------------- |
| **Pipeline**                                                                              | up to -3          |
| **Model 1 (Baseline):** Not implemented / Conceptual error / No appropriate justification | -1 each, up to -3 |
| **Model 2:** Not implemented / Conceptual error / No appropriate justification            | -1 each, up to -3 |
| **Model 3:** Not implemented / Conceptual error / No appropriate justification            | -1 each, up to -3 |


---

## 5b. Model Assessment and Hyperparameter Tuning (+8 points) ✖️✖️


| Condition                                                                                                                                                                                                                                                                                                      | Penalty |
| -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------- |
| Flawless: uses multiple assessment metrics correctly in understanding model performance, performs methodical approach to hyperparameter and parameter tuning, offers sufficient rationale for new design implementations and changes                                                                           | -0      |
| Hyper-parameter Tuning Missing: missing hyper-parameter tuning in any one of the models *(stackable)*                                                                                                                                                                                                          | -2      |
| Missing/Inappropriate Evaluation Metrics: does not use any form of evaluation metric, or inappropriate choice of evaluation metric *(stackable)*. E.g. using "accuracy" for a classification of severely imbalanced dataset; using a regression evaluation metric for a classification problem (or vice versa) | -2      |
| Conceptual Error: lacks methodical and iterative approach in implementing changes in training any one of the models *(stackable)*. E.g. deciding to increase model complexity despite training and validation curves clearly indicating overfitting                                                            | -2      |
| Evaluation/Justification Missing: fails to communicate the rationale of the model design decisions made in relation to the project objectives *(stackable)*. E.g. only reporting the performance results of best models but not comparing them with previous models                                            | -2      |
| Not at all: no model assessment or hyperparameter tuning attempted                                                                                                                                                                                                                                             | -8      |


---

## 6. Visualization (+8 points) ✖️

> **Note:** Interactive visualizations should be captured in a short video included in the project submission, or runnable without having to re-run the notebook.


| Grade                       | Description                                                                                                                                                                                                                                       | Penalty |
| --------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------- |
| Outstanding                 | In addition to clear, appropriate, well-formatted visualizations, the team incorporated diverse and unique plots with sufficient justification. Diverse plots add a deeper level of understanding to the overall project.                         | -0      |
| Clear and Interpretable     | Each and every visualization is clear, easy to interpret, includes appropriate titles, axes labels, non-overlapping elements, etc. All visualizations come with a brief explanation. Each visualization serves a purpose and adds to the project. | -2      |
| Inconsistencies Present     | All visualizations are appropriate, but had some inconsistencies (e.g. some missing titles, axes labels, etc.). Some plots are superfluous and detract from the larger meaning.                                                                   | -4      |
| Conceptual Misunderstanding | Inappropriate/unintuitive graphs have been used in some cases (e.g. something other than a line chart was used for time-based trends, etc.)                                                                                                       | -6      |
| Low Effort/None at all      | No visualization, lacking significant visualizations, OR charts included reflect very low effort and attention to detail.                                                                                                                         | -8      |


---

## 7. Code Quality/Readability (+8 points) ✖️


| Grade             | Description                                                                                                                                                                     | Penalty |
| ----------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------- |
| Excellent         | Code is totally readable, broken into logical sections, easy to follow, and appropriate in-line code comments are provided when helpful.                                        | -0      |
| Good              | Slightly difficult to follow, e.g. not broken down into logical blocks. For the most part, a third person can look at the code and tell the story with only minor difficulties. | -3      |
| Needs Improvement | Notebook is very difficult to follow; code is difficult to understand because comments are absent when necessary for a third-person to understand.                              | -6      |
| Poor              | No code or large portions of code are missing (i.e. an incomplete project)                                                                                                      | -8      |


---

## 8. Application of Course Topics (+8 points) ✖️

**Eligible course topics:**

- ☑️ Pandas
- ☑️ PandaSQL
- ☑️ Regex
- ☑️ `JOIN`
- ☑️ Unsupervised Learning models
- ☑️ Supervised Learning models
- ☑️ Conditioning on predictive vs. interpretable models
- ☑️ ER Diagram (If multiple tables used)
- ☑️ 3NF
- ☑️ Polar
- ☑️ DuckDB
- ☑️ Hypothesis Testing
- ☑️ Bootstrapping

> If any of these is used **without logical conditioning** on how the concept is relevant to the overall goal of the project, use of concept will not be counted.
>
> **Examples of uncounted usage:**
>
> 1. In a classification project, a student runs a K-Means algorithm as a stand-alone model without incorporating cluster results as a feature.
> 2. A dataset only has 1 table, and the team provided an ER diagram.


| Grade     | Description                              | Penalty |
| --------- | ---------------------------------------- | ------- |
| Excellent | Incorporated at least 5 of the above     | -0      |
| Good      | Incorporated 3-4 of the above            | -2      |
| Mediocre  | Incorporated only 2 of the above         | -4      |
| Poor      | Incorporated only 1 of the above         | -6      |
| None      | No course topics included in the project | -8      |


---

## 9. Quality of Annotated Notebook (+8 points) ✖️


| Grade        | Description                                                                                                                                                                                                                                                           | Penalty |
| ------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------- |
| Excellent    | Clean and completely self-contained Annotated Notebook with clear and navigable sections. All visualizations are explained. Annotated Notebooks must be fully-ran with no error messages/bugs.                                                                        | -0      |
| Good         | Mostly good final deliverable with a few inconsistencies, unclear portions, or unprofessional elements. Most visualizations are explained. Very frequent typos or other signs that the final deliverable was not quality-checked before submission will be penalized. | -2      |
| Average      | Provides a final deliverable that has substance, but is visually/verbally difficult to follow. Many visualizations are not explained/interpreted/justified.                                                                                                           | -4      |
| Poor         | Provides a deliverable that is hard to follow or not at all self-contained/self-explanatory. Demonstrates lack of understanding and/or professional appeal.                                                                                                           | -6      |
| Unacceptable | Neither clean nor engaging final deliverable.                                                                                                                                                                                                                         | -8      |


---

## 10. Quality of Sectional Summary (+8 points) ✖️

**Annotated Notebook should include the following detailed write-up:**

- **Introduction and Background:** introduce problem statement, objective and value proposition of the project, an overview of dataset, EDA highlights, etc.
- **Approach/Methods:** describe algorithms used (and why), end-to-end pipeline
- **Results:** how did the models perform and how did they compare to each other, why?
  - ☑️ Appropriate use of visuals to convey results
- **Conclusion and Discussion:** key takeaways, implications of modeling result, and future work
  - For interpretable models: ☑️ Feature importance
  - For non-interpretable models: ☑️ Factors most improve model performance and why
  - For both:
    - ☑️ Modeling implications for potential stakeholders
    - ☑️ Model limitation
    - ☑️ Potential improvement (other models to test or data to add) / future work


| Grade     | Description                                                                     | Penalty |
| --------- | ------------------------------------------------------------------------------- | ------- |
| Excellent | Discussion of each component is logical and thorough.                           | -0      |
| Good      | Discussion of each component is fine, with one component not covered in depth.  | -2      |
| Average   | Discussion of each component is fine, with 2-3 components not covered in depth. | -4      |
| Poor      | Lack of insightful discussion on any of the components.                         | -6      |
| Missing   | No discussion on any of these topics whatsoever.                                | -8      |


---

## 11. Quality of Presentation (+20 points) ✖️✖️

Along with your annotated notebook, you will also be required to submit a presentation to the TAs and professors grading your project. Presentations can be done via recorded video or live if you would like.

> **Requirements for video presentations:** The face of the person speaking must be visible, and you are required to use your own voices for audio.

**Required components:**

- ☑️ Objective, value proposition, and dataset used
- ☑️ Major learnings from EDA (with top 3-5 well-formatted charts that deepened your understanding of the dataset and informed your model)
- ☑️ Modeling results (models used, performance, etc)
- ☑️ Implications and insights
- ☑️ Challenges/limitations/potential future work

> Not all group members are required to speak during the presentation.


| Condition                                                                                                                                    | Penalty |
| -------------------------------------------------------------------------------------------------------------------------------------------- | ------- |
| Excellent: Presentation addressed all requested sections, and delivered a clean and engaging presentation. All visuals used are informative. | -0      |
| Missing section: presentation missing any of the requested sections OR the content of any section is poorly discussed *(stackable)*          | -5      |
| Missing/inappropriate visuals: did not use visuals or visuals are irrelevant to topics discussed *(stackable)*                               | -5      |
| Under/Over-time: presentation is less than 8 or over 10 mins *(stackable)*                                                                   | -5      |
| Unpolished presentation: contains various typos, codes, or inconsistent formats that make the presentation look unprofessional *(stackable)* | -5      |
| No Submission: missing                                                                                                                       | -20     |


---

## 12. Other Penalties ✖️✖️


| Condition                                                                                                                                           | Penalty |
| --------------------------------------------------------------------------------------------------------------------------------------------------- | ------- |
| All Good                                                                                                                                            | -0      |
| Late Final Deliverable                                                                                                                              | Vary    |
| Project Contribution Issue: Teammates will have the opportunity to provide feedback. Individual grades will be a direct reflection of contribution. | Vary    |
| Others                                                                                                                                              | Vary    |


