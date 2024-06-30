# Team Project

# Mortgage Risk Assessment Project

## Project Overview

Welcome to the Mortgage Risk Assessment Project! This project aims to analyze and predict mortgage loan amounts and assess loan conditions (Good Loan vs. Bad Loan) using various machine learning techniques. Our team has designed, implemented, and tested regression and classification models to gain insights into the factors affecting loan amounts and conditions.

## Team Members

- **dogagzm**
- **krishnakishore163**
- **movcha**
- **shiyamhoda**

## Project Structure

The project is divided into several parts:
1. **Linear Regression Analysis**: Predicting loan amounts based on features such as annual income, employment length, interest rate, debt-to-income ratio, and grade category.
2. **Logistic Regression Analysis**: Classifying loans as 'Good' or 'Bad' based on the same set of features.
3. **Random Forest Classifier**: Improving loan condition classification using a Random Forest classifier.

**Design:**
- **Features:** `annual_inc`, `emp_length_int`, `interest_rate`, `dti`, `grade_cat`
- **Target:** `loan_amount`

**Findings:**
Impact of Borrower Characteristics on Mortgage Risk
Regression Analysis
- **Linear Regression**: Identified key borrower characteristics such as annual income, employment length, interest rate, debt-to-income ratio, and credit grade significantly influencing loan amounts.
- **Logistic Regression**: Highlighted significant predictors of loan condition, confirming the importance of borrower characteristics in determining mortgage risks.
- **Random Forest Classifier**: Provided robust classification of loan conditions, reinforcing findings from regression analyses.

**Conclusion:**
This project provides comprehensive insights into how borrower characteristics influence mortgage risks. By analyzing diverse datasets and employing robust methodologies, the findings offer valuable guidance for policymakers, lenders, and borrowers, aiding in informed decision-making and risk management.

**Next Steps:**
Future work may include:

Incorporating additional economic indicators.
Enhancing model performance with advanced techniques.
Deploying models for real-time risk assessment.

## Progress Report

### 2024-06-17
- Group chat in Slack was created before the Team Project pt.I day 1, thanks Shiyam
- Established a constant point of contact
- Initiated thinking about the project topic

### 2024-06-18
**On a Meeting:**
- First team meeting getting to know each other
- Shared background of team members
- Decided on a project topic direction: mortgages and mortgage risk assessment
- All team members agreed to look through the given datasets list for data connected with mortgages, loans, interest rates, house prices, and so on

**Independent Work:**
- Each team member explored the datasets list for relevant data

### 2024-06-19
- From the options proposed by each team member, one dataset was selected
- Cleaned data by removing irrelevant column attributes and sampling data on certain dates to reduce the overall file size so that it can be uploaded to GitHub

...

### 2024-06-30
- finalizing the project, creating a readme file and recording a video
- recording a video

- Sources and references utilized for this project can be accessed in:
  - [Data folder](./data/)
  - [Source Code and Models](./src/)

   **Links to individual videos**

- **dogagzm**
- **krishnakishore163**
- **movcha**
- **shiyamhoda**

<details>
<summary>Original Team Project Requirements</summary>

## Description

The team project consists of two modules. Each module requires participants to apply the skills they have learned to date, and explore a dataset of their choosing. The first part of the team project involves creating a simple program with a database in order to analyze a dataset from an open source, such as Kaggle. In the second part of the team project, teams will come together again and apply the skills developed in each of the data science or machine learning foundations certificate streams. Teams will either create a data visualization or a machine learning model.



Participants will work in assigned teams of 4-5. 

#### Project Descriptions

* [First Team Project Description](./team_project_1.md)
* [Second Team Project Description](./team_project_2.md)

## Learning Outcomes
By the end of Team Project Module 1, participants will be able to:
* Resolve merge conflicts
* Describe common problems or challenges a team encounters when working collaboratively using Git and GitHub
* Create a program to analyze a dataset with contributions from multiple team members

By the end of Team Project Module 2, participants will be able to:
* Create a data visualization as a team
* Create a machine learning model as a team

### Contacts
**Questions can be submitted to the _#cohort-3-help_ channel on Slack**

* Technical Facilitator: 
  * **Phil Van-Lane**(he/him)
  phil.vanlane@mail.utoronto.ca

* Learning Support Staff:
  * **Taneea Agrawaal** (she/her)
  taneea@cs.toronto.edu
  * **Farzaneh Hashemi** (she/her )
  fhashemi.ma@gmail.com
  * **Tong Su** (she/her)
  tong.su@mail.utoronto.ca

### Delivery of Team Project Modules

Each Team Project module will include two live learning sessions and one case study presentation. During live learning sessions, facilitators will introduce the project, walk through relevant examples, and introduce various team skills that support project success. The remaining time will be used for teams to assemble and work on their projects, as well as get help from the facilitator or the learning support to troubleshoot any issues a team may be encountering. 

Work periods will also be used as opportunities for teams to collaborate and work together, while accessing learning support. 

### Schedule

|Day 1|Day 2|Day 3|Day 4|Day 5|
|-----|-----|-----|-----|-----|
|Live Learning Session |Live Learning Session|Case Study|Work Period|Work Period|

## Requirements
* Participants are expected to attend live learning sessions and the case study as part of the learning experience. Participants are encouraged to use the scheduled work period time to complete their projects.
* Participants are encouraged to ask questions and collaborate with others to enhance learning.
* Participants must have a computer and an internet connection to participate in online activities.
* Participants must not use generative AI such as ChatGPT to generate code to complete assignments. It should be used as a supportive tool to seek out answers to questions you may have.
* We expect participants to have completed the [onboarding repo](https://github.com/UofT-DSI/onboarding/tree/main/onboarding_documents).
* We encourage participants to default to having their camera on at all times, and turning the camera off only as needed. This will greatly enhance the learning experience for all participants and provides real-time feedback for the instructional team. 

### How to get help
![image](/steps-to-ask-for-help.png)

## Folder Structure

### Project 1
```markdown
|-- data
|---- processed
|---- raw
|---- sql
|-- reports
|-- src
|-- README.md
|-- .gitignore
```

### Project 2
```markdown
|-- data
|---- processed
|---- raw
|---- sql
|-- experiments
|-- models
|-- reports
|-- src
|-- README.md
|-- .gitignore
```

* **Data:** Contains the raw, processed and final data. For any data living in a database, make sure to export the tables out into the `sql` folder, so it can be used by anyone else.
* **Experiments:** A folder for experiments
* **Models:** A folder containing trained models or model predictions
* **Reports:** Generated HTML, PDF etc. of your report
* **src:** Project source code
* README: This file!
* .gitignore: Files to exclude from this folder, specified by the Technical Facilitator

</details>

