# Team Projects

## Project #1: Impact of Minimum Wage Changes on Unemployment Rates in Canada
### Executive Summary

This project presents findings from an extensive analysis exploring the impact of minimum wage changes on unemployment rates across Canadian provinces in 1976-2024. Leveraging datasets from [Statistics Canada](./data/raw/unemployment_rates_data.csv) and the [Government of Canada](./data/raw/minimum_wage_data.csv), the team conducted thorough data analysis and regression modeling to investigate the relationships between minimum wage adjustments and unemployment dynamics. Key findings reveal significant variations across provinces, underscoring the influence of regional economic contexts on policy outcomes. These insights are vital for informing stakeholders about the implications of minimum wage policies on labor market dynamics.

### Project Overview

The project focused on analyzing labor market dynamics in Canada with a specific emphasis on minimum wage policies and their effects on unemployment rates. Through meticulous data selection, cleaning, and statistical modeling, our team aimed to uncover correlations and patterns between minimum wage changes and unemployment trends across different provinces.

### Dataset Selection

Datasets were chosen based on rigorous criteria:

- **Relevance**: Included variables pertinent to minimum wage and unemployment rates across Canadian provinces.
- **Completeness**: Ensured minimal missing values and comprehensive coverage over significant time periods.
- **Accuracy**: Sourced data from reliable authorities such as Statistics Canada.
- **Format**: Preferred formats were CSV and Excel for compatibility with statistical software.

### Team Collaboration

Effective collaboration was achieved through:

- **Defined Roles**: Team members were assigned roles based on expertise in data cleaning, analysis, visualization, and project management.
- **Regular Meetings**: Scheduled meetings facilitated progress updates, decision-making, and feedback incorporation.
- **Shared Workspace**: Utilized GitHub for version control and Slack for real-time communication to streamline collaboration and documentation.
- **Documentation**: Maintained detailed records to track project progress, methodologies, and decisions throughout the project lifecycle.

![project board](./src/img/image.png)

### Decision-Making Process

Decision-making was guided by:

- **Consensus-Based Approach**: Encouraged open discussions to gather input from all team members on critical decisions.
- **Voting**: Employed for resolving disagreements and making key project decisions when consensus was challenging.
- **Lead Roles**: Designated leads for specific project components to enhance accountability and streamline decision processes.
- **Feedback Loop**: Established mechanisms for continuous feedback to address concerns promptly and optimize project outcomes iteratively.

### Research Questions

The analysis aimed to answer the following research questions:

- What is the impact of minimum wage changes on unemployment rates in Canada and across different provinces?

### Model
- The following linear regression model was used to test the hypothesis if minimum wage increases affect unemployment rates across provinces: 

![Model Unemployment rates vs Wage increases across Canadian provinces](./src/img/model_provinces.png)

- The following linear regression model was used to test the hypothesis if minimum wage increases affect unemployment rates in Canada:

  - :nerd_face:  Unemployment Rate = $B_0$ + $B_1$ x Minimum Wage

## Findings: Impact of Minimum Wage Changes

### Regression Analysis for Canada

- Identified a statistically significant negative relationship (-0.3137 coefficient) between minimum wage and unemployment rate across Canada. 

- The $𝑅^{2}$ value of 0.337 indicated that 33.7% of unemployment rate variation can be explained by minimum wage fluctuations. [More details](https://github.com/hitechparadigm/team_project/blob/team-project-1/src/regression_Canada_average.ipynb)

![Model Unemployment rates vs Wage increases in Canada 1976-2024](./src/img/Canada_UR_MW_model_summary.png)


**Plot Interpretation**

The scatter plot with the regression line shows that as the minimum wage increases, the unemployment rate tends to decrease, reinforcing the negative correlation observed in the regression analysis.

![Model Unemployment rates vs Wage increases in Canada 1976-2024](./src/img/Canada_UR_MW.png)


### Regional Variations by provinces:

- **Provincial Analysis**: Revealed diverse sensitivities to minimum wage changes; provinces like Quebec and New Brunswick exhibited strong correlations (e.g., $𝑅^{2}$ = 0.592 for Quebec), whereas Saskatchewan and Ontario displayed weaker correlations, suggesting influential roles of other economic factors. [More details](https://github.com/hitechparadigm/team_project/blob/team-project-1/src/regression_provinces.ipynb)

**Strong Negative Correlation Provinces**

- **Newfoundland and Labrador, New Brunswick, Quebec:**
  - These provinces show a strong negative correlation between minimum wage and unemployment rates, suggesting that increases in minimum wage lead to notable decreases in unemployment. This might reflect robust local economies where higher wages boost consumer spending and overall economic activity, thereby creating more jobs.

**Moderate Negative Correlation Provinces**

- **Prince Edward Island, Nova Scotia, Manitoba, British Columbia:**
  - These provinces also exhibit a negative correlation, though to a lesser extent. The decrease in unemployment rates with higher minimum wages indicates beneficial effects, albeit less pronounced compared to the strong correlation provinces.

**Weak Negative Correlation Provinces**

- **Ontario, Saskatchewan:**
  - The weak negative correlations suggest that while higher minimum wages slightly reduce unemployment rates, the impact is minimal. This could be due to diverse economic activities and employment structures that dilute the direct effect of wage increases.

**No Significant Correlation**

- **Alberta:**
  - The lack of significant correlation in Alberta indicates that other factors overshadow the influence of minimum wage on unemployment rates. Alberta's economy, heavily influenced by the oil and gas industry, might have unique dynamics that decouple minimum wage changes from unemployment rates.

### Economic Insights and Future Research

Future research should delve into additional factors influencing unemployment rates and refine our understanding of Canadian labor market dynamics.

Key areas for future analysis include:

- Continued monitoring of minimum wage impacts on unemployment rates at national and provincial levels.
- Tailoring minimum wage policies to regional economic conditions and industry-specific factors.
- Exploration of broader economic contexts beyond minimum wage adjustments.

### Conclusion

:slightly_smiling_face:  This project contributes comprehensive insights into how minimum wage policies influence unemployment rates across Canadian provinces. By analyzing diverse datasets and employing robust methodologies, the findings provide valuable guidance for policymakers, businesses, and the public, aiding in informed decision-making and policy formulation.

Overall, the observed negative correlations between minimum wage and unemployment rates in most provinces suggest that :sparkles:**increasing the minimum wage can have positive economic effects**:sparkles: , such as reducing unemployment and improving living standards for low-wage workers. These findings align more closely with contemporary economic theories like Keynesian economics and efficiency wage theory, rather than classical economic theory.

Whether higher minimum wages are "good" or "bad" depends on the balance between the positive impacts on worker incomes and economic demand, and the potential challenges faced by businesses and specific sectors. Policymakers need to consider these factors and regional economic conditions when setting minimum wage levels to maximize the benefits and minimize potential downsides.

### Appendix

**References**

- Sources and references utilized for this project can be accessed in:
  - [Data folder](./data/)
  - [Reports](./reports/)
  - [Source Code and Models](./src/)

- **Links for individual videos**
  - [Janaparan (Jay)](https://drive.google.com/file/d/11ADMGfVLlmB0PGKVE3AiGE1pYGqM6N8i/view?usp=sharing)
  - [Yixi (Grace) Gong](https://drive.google.com/file/d/1b2MJgBqacibr2kWKau7u20XTyQvTsM1M/view?usp=sharing)
  - [Dmytro Malyk](https://drive.google.com/file/d/1L2M0-74dwFq_ldhs-Akx24oWjtj3apIa/view?usp=sharing)
  - [Phoebe Z Wei](https://)
  - [Yuriy Koshulap](https://drive.google.com/file/d/1rEz-Txkpv3KhujvFx-V1Mg3qXSxhqbcX/view?usp=sharing)







<details>
<summary>Original Requirements - cohort #3</summary>

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
