INTRODUCTION :
1. Our emotional, psychological, and social well-being are all part of our mental health. It has the potential to influence our interactions with others, as well as our professional performance and physical wellness. 
2. The problem of mental health is receiving an increasing amount of attention these days.
3. For persons with mental illnesses, having a positive attitude toward obtaining therapy is critical.
4. According to WHO (2005) high stress, long hours of labor, work pressure,and the desire to make a name for oneself characterize people in technical sectors. Perez and Wilkerson (1998) mentioned that stress is quickly becoming the most common cause of worker incapacity; according to a poll, stress is responsible for 40% of job turnover, and 25% of workers consider work to be their greatest source of stress.

PROBLEM STATEMENT :
1. This analysis aims to understand factors contributing the mental health of a person.
2. The dataset measures mental health attitudes and frequency of mental health disorders in the tech workplace.
3. The project will systematically explore workplace mental health, starting with a comprehensive explanation of dataset and perform EDA.

DATASET :
	The dataset consists of data on employee attitudes about mental health in the tech industry, as well as geographic and demographic statistics and workplace support. It is based on a 2014 survey conducted by an open-source mental illness platform, which found that 1260 participants reported mental health difficulties. The data is mainly focused on mental health reports in the tech industry, indicating that individuals are more likely to work at a tech-focused company.

COLUMN DESCRIPTIONS :
1. Timestamp : Time the respondent took this questionnaire.
2. Age: Age of a person
3. Gender: If a person is male ,female or other.
4. Country: Country of respondent
5. state:Which state or territory do you reside in if you are a US citizen?
6. self_employed:Do you work for yourself?
7. family_history:Do you have a history of mental illness in your family?
8. treatment:Have you received therapy for a mental illness?
9. work_interfere:do you think having a mental illness affects your ability to accomplish your job?
10. no_employees:How many people work for your company
11. remote_work:Do you spend at least 50% of your time working remotely
12. Tech_company:Is your employer mostly a tech business or organization?
13. Benefits:Do you receive menthol health benefits from your employer.
14. care_options:Do you know what choices your employer offers for mental health care?
15. Wellness_program:Has your organization ever covered mental health as a part of a wellness initiative for employees?
16. Seek_help:Does your workplace offer information about mental health issues and how to get help?
17. Anonymity:If you decide to use resources for mental health or drug misuse therapy, is your privacy protected?
18. Leave:How simple is it for you to request a leave of absence for a mental health issue?
19. Mental health consequence:Do you believe that disclosing a mental health issue to your workplace would have unfavorable effects?
20. Phys health consequence:Do you believe there would be drawbacks if you discussed a physical health issue with your employer?
21. Coworkers:Would you be open to having a conversation with your coworkers about a mental health issue?
22. Phys health interview:In a job interview, would you bring up a physical health concern?
23. Mental vs physical:Do you think your employer treats mental health and physical health equally seriously?
24. Obs_consequence:Have you heard of or seen unfavorable working outcomes for employees who have mental health issues?
25. comments:Any additional notes or comments

DATA CLEANING :
1. The analysis aims to understand factors contributing to a person's mental health in the tech workplace.
2. The dataset contains information on mental health attitudes and the frequency of mental health disorders in the tech workplace.
3. There are 26 columns in the dataset.
4. Most columns are of object data type, except for the age column.
5. The comment column has a high number of null values, which is expected as it was optional for respondents to fill.
6. The timestamp column will be dropped as it contains irrelevant information for the analysis.
7. The state and country columns will also be dropped due to a large number of null values and potential biases.
8. Some age values are negative and below 15, which need to be corrected as they are not legally allowed to work.
9. The gender column will be cleaned and combined into categories like Male, Female, and Other.
10. The dataset has around four times more males than females, which must be considered to avoid biased assumptions.
11. Two columns, 'work_interfere' and 'self_employed,' contain null values, which will be filled with 'Don't Know' and 'NOT self_employed,' respectively.
12. The data will be prepared for further processing after handling the null values.

In the next phase of our project, we delve into the heart of our cleaned dataset, embarking on a comprehensive Exploratory Data Analysis (EDA) to uncover valuable insights and patterns surrounding workplace mental health.
