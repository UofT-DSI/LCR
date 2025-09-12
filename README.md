# Linear regression, classification, and resampling

## Content
* [Description](#description)
* [Learning Outcomes](#learning-outcomes)
* [Assignments](#assignments)
* [Contacts](#contacts)
* [Delivery of the Learning Module](#delivery-of-the-learning-module)
* [Schedule](#schedule)
* [Requirements](#requirements)
* [Resources](#resources)
  - [Documents](#documents)
  - [Simple Linear Regression](#simple-linear-regression)
  - [Multiple linear regression, interactions, qualitative predictors](#multiple-linear-regression-interactions-qualitative-predictors)
  - [Classification (logistic regression, generative models)](#classification-logistic-regression-generative-models)
  - [Resampling methods (CV, bootstrap) and Linear model selection and regularization](#resampling-methods-cv-bootstrap-and-linear-model-selection-and-regularization)
* [Folder Structure](#folder-structure)

## Description

This module introduces the skills required to design, implement, and test basic statistical learning methods, including regression, classification, and clustering, as well as validating models with resampling techniques. It compares the differences between modeling for prediction purposes and inference, exploring the trade-offs between prediction accuracy, model interpretability, and the bias-variance trade-off. Participants also gain exposure to key tools such as Pandas, NumPy, and scikit-learn.

## Learning Outcomes

By the end of the module, participants will be able to:

- Implement and interpret the results from several supervised learning approaches for classification and regression.
- Use resampling methods such as cross-validation and bootstrapping to select and evaluate models.
- Understand the requirements for reproducible machine learning and ensure consistency across model implementations.
- Analyze the uncertainties and limitations associated with model results and understand the ethical implications of applying these models in real-world decision-making.
- Explain the trade-offs and considerations of various statistical methods to both technical and non-technical audiences.
- Apply `pandas`, `numpy`, and `scikit-learn` for data manipulation, model implementation, and evaluation.

## Assignments

Participants should review the [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md) for instructions on how to complete assignments in this module.

[Assignment 1](./02_activities/assignments/assignment_1.ipynb)

[Assignment 2](./02_activities/assignments/assignment_2.ipynb)

[Assignment 3](./02_activities/assignments/assignment_3.ipynb)

**Assignment Due Dates**

| Assessment   | Content                            | Due Date     |
|--------------|------------------------------------|--------------|
| Assignment 1 | Classification (Sessions 1, 2)     | Sept 7 |
| Assignment 2 | Regression (Sessions 3, 4)         | Sept 14    |
| Assignment 3 | Clustering & Resampling (Sessions 5, 6) | Sept 21   |

### Contacts
**Questions can be submitted to the _#cohort-6-help_ channel on Slack**
* Technical Facilitator: **Julia**. Questions can be sent via [Slack](https://uoft-dsi-certificates.slack.com/team/U06D4QM7YEA)
* Learning Support Staff: **Ernani**. Questions can be sent via [Slack](https://uoft-dsi-certificates.slack.com/team/U06V88X2X3N)
* Learning Support Staff: **Edward**. Questions can be sent via [Slack](https://uoft-dsi-certificates.slack.com/team/U090NAV8Z8U)
* Learning Support Staff: **Gayathri**. Questions can be sent via [Slack](https://uoft-dsi-certificates.slack.com/team/U08R6URRSCT)

### Delivery of the Learning Module

This module will include live learning sessions and optional, asynchronous work periods. During live learning sessions, the Technical Facilitator will introduce and explain key concepts and demonstrate core skills. Learning is facilitated during this time. Before and after each live learning session, the instructional team will be available for questions related to the core concepts of the module. Optional work periods are to be used to seek help from peers, the Learning Support team, and to work through the homework and assignments in the learning module, with access to live help. Content is not facilitated, but rather, this time should be driven by participants. We encourage participants to come to these work periods with questions and problems to work through. 
 
Participants are encouraged to engage actively during the learning module. The key to developing the core skills in each learning module is through practice. The more participants engage in coding with the instructional team and apply the skills in each module, the more likely these skills will solidify. 

The technical facilitator will introduce the concepts through a collaborative live coding session using the Python notebooks, which can be found under `/01_materials/notebooks/`. Slides can be found under `/01_materials/slides/`.

## Schedule
- Week 1 will focus on intro and classification methods
- Week 2 will focus on regression methods
- Week 3 will focus on clustering and statistical inference topics

### Requirements

* Participants are expected to have completed Shell, Git, and Python learning modules.
* Participants are encouraged to ask questions and collaborate with others to enhance learning.
* Participants must have a computer and an internet connection to participate in online activities.
* Participants must not use generative AI such as ChatGPT to generate code to complete assignments. It should be used as a supportive tool to seek out answers to questions you may have.
* We expect participants to have completed the steps in the [onboarding repo](https://github.com/UofT-DSI/onboarding/blob/main/environment_setup/README.md).
* We encourage participants to default to having their camera on at all times and turning the camera off only as needed. This will greatly enhance the learning experience for all participants and provides real-time feedback for the instructional team. 

## Resources
Feel free to use the following as resources:

### Documents
<!-- - [Cheatsheet](./04_cohort_three/additional_resources/05_review_session_material/dsi_emlt_cheat_sheet_2.pdf)
- [Cross Validation - Basic Idea and Steps](./04_cohort_three/additional_resources/05_review_session_material/cross_validation_basic_idea_and_steps.pdf)
- [EMLT Tutorial](./04_cohort_three/additional_resources/05_review_session_material/emlt_tutorials.pdf) -->
- Textbook: [Data Science: A First Introduction](https://python.datasciencebook.ca/index.html)
- [Introduction to Statistical Learning with Python Documentation (ISLP)](https://islp.readthedocs.io/en/latest/index.html)
- [Introduction to Machine Learning with Python](https://www.nrigroupindia.com/e-book/Introduction%20to%20Machine%20Learning%20with%20Python%20(%20PDFDrive.com%20)-min.pdf)

### Videos 
- [Introduction to Statistical Learning with Python Video Playlist](https://www.youtube.com/playlist?list=PLoROMvodv4rPP6braWoRt5UCXYZ71GZIQ)

#### Simple Linear Regression
- [Linear Regression, explained in 2 minutes](https://www.youtube.com/watch?v=CtsRRUddV2s)
- [Linear Regression, Clearly Explained!!!](https://www.youtube.com/watch?v=7ArmBVF2dCs&pp=ygUic2ltcGxlIGxpbmVhciByZWdyZXNzaW9uIHN0YXRxdWVzdA%3D%3D)

#### Multiple linear regression, interactions, and qualitative predictors
- [Multiple Regression, Clearly Explained!!!](https://www.youtube.com/watch?v=EkAQAi3a4js&pp=ygUic2ltcGxlIGxpbmVhciByZWdyZXNzaW9uIHN0YXRxdWVzdA%3D%3D)

#### Classification (logistic regression, generative models)
<!-- - [Logistic Regression, explained in 3 minutes](https://www.youtube.com/watch?v=EKm0spFxFG4)
- [StatQuest: Logistic Regression](https://www.youtube.com/watch?v=yIYKR4sgzI8&list=PLblh5JKOoLUKxzEP5HA2d-Li7IJkHfXSe)
- [StatQuest: Linear Discriminant Analysis (LDA) clearly explained.](https://www.youtube.com/watch?v=azXCzI57Yfc&pp=ygUNTERBIHN0YXRxdWVzdA%3D%3D) -->
- [StatQuest: K-nearest neighbors, Clearly Explained](https://www.youtube.com/watch?v=HVXime0nQeI&pp=ygUNa25uIHN0YXRxdWVzdA%3D%3D)
<!-- - [Naive Bayes, Clearly Explained!!!](https://www.youtube.com/watch?v=O2L2Uv9pdDA&pp=ygUaYmF5ZXMgY2xhc3NpZmllciBzdGF0cXVlc3Q%3D)
- [Generalized Linear Model](https://www.youtube.com/watch?v=SqN-qlQOM5A) -->

#### Resampling methods (CV, bootstrap) and Linear model selection and regularization
<!-- - [Linear Modelling](https://www.youtube.com/watch?v=-inJu1jHqb8) -->
- [Machine Learning Fundamentals: Cross Validation](https://www.youtube.com/watch?v=fSytzGwwBVw&pp=ygUYdmFsaWRhdGlvbiBzZXQgc3RhdHF1ZXN0)
- [Bootstrapping Main Ideas!!!](https://www.youtube.com/watch?v=Xz0x-8-cgaQ&pp=ygUXYm9vdHN0cmFwcGluZyBzdGF0cXVlc3Q%3D)
- [Bootstrapping Method](https://www.youtube.com/watch?v=uGsf3spCM3Y)
- [$k$-fold Cross Validation](https://www.youtube.com/watch?v=TIgfjmp-4BA)

Alternative Textbook: [Data Science: A First Introduction](https://python.datasciencebook.ca/classification1.html) (Chapters 5-10)

## Folder Structure

```markdown
.
├── .github
├── .gitignore
├── 01_materials
├── 02_activities
├── 03_instructional_team
├── 04_this_cohort
├── LICENSE
├── SETUP.md
└── README.md
```

* **.github**: Contains issue templates and pull request templates for the repository.
* **materials**: Module slides (.pdf) used during learning sessions.
* **activities**: Contains assignments.
* **instructional_team**: Resources for the instructional team.
* **this_cohort**: Additional materials and resources for this cohort.
* **.gitignore**: Files to exclude from this folder, specified by the Technical Facilitator
* **LICENSE**: The license for this repository.
* **SETUP.md**: Contains the instructions for creating and activating the environment, and installing any packages needed for this specific module.
* **README.md**: This file.

