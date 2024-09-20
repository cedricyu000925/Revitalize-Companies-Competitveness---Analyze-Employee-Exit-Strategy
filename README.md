# [Revitalize Companies Competitveness --- Analyze Employee Exit Strategy]

## INTRODUCTION
For this project, we’ll assume the role of data analysts for the Department of Education, Training and Employment (DETE) and the Technical and Further Education (TAFE) institute in Queensland, Australia to analyze employee exit surveys and uncover insights about why employees resign.

In this project, I used Google Colab, Python (for dataframe manipulating and data visualization), and Microsoft Excel csv files to analyze the abovementioned surveys to get insights about:

  1. Are employees who only worked for the institutes for a short period of time resigning due to some kind of dissatisfaction? What about employees who have been there longer?
  2. Are younger employees resigning due to some kind of dissatisfaction? What about older employees?

After analyzing both the DETE and TAFE surveys, I have found out that:

   **Finding 1)**
   
   People who worked 7 to 10 years in the same company or institution were more common to have dissatisfaction. People who are new to their previously served institution or have been worked there for 3 to 6 years share a considerable amount of dissatisfaction as well.

  
   **Finding 2)**
   
   Younger people (we are talking about 21 to 30 years old employees) do have a considerable amount of dissatisfaction, but it is actually most common for employees who are 41 to 55 years old to have dissatisfaction towards their insitution.

### Finding 1) It is most common for those who are established in their own insitution to harbor dissatisfaction
To briefly explain the labels:

**New**: Less than 3 years at a company

**Experienced**: 3-6 years at a company

**Established**: 7-10 years at a company

**Veteran**: 11 or more years at a company


![Finding 1](https://github.com/user-attachments/assets/ccc34fdb-b66c-4a4b-ad16-b23babbcadde)

After analyzing the exit surveys from the Department of Education, Training and Employment (DETE) and the Technical and Further Education (TAFE) institute, it became apparent that dissatisfaction levels vary significantly with the length of service. Employees who have been with their institution for **7 to 10 years, labeled as "Established,"** show a higher prevalence of dissatisfaction compared to other groups (33%). This suggests that mid-career employees might face specific challenges that contribute to their decision to resign.

While less pronounced than the "Established" employees, **"New" and "Experienced" (worked 3 to 6 years)** employees also share a moderately high amount of dissatisfaction towards their company (26% and 25% respectively). It is possible that as employees become more familiar with the institutional culture and expectations, they begin to encounter limitations in career growth or job satisfaction.

According to this bar chart, **"Veteran"(those who worked 11 years or more)** employees have the least amount of dissatisfaction towards their company (3%). It is possible that veteran employees might experience either renewed satisfaction due to stability and recognition.

### Finding 2) BOTH young people and middle-aged people express a high level of dissatisfaction

![Finding 2a](https://github.com/user-attachments/assets/81552025-d499-4482-b324-7d0d42c274f5)

![Finding 2b](https://github.com/user-attachments/assets/0f559f7f-f005-47b4-9a2d-15f62fff65ea)

By independently examining and analyzing the TAFE survey, I found out that 340 people resigned their previous job. Among these 340 people, 117 people resigned due to some dissatisfaction towards their last job, which is 34% of all people who indicated that they resigned their last position.

Among these 117 dissatisfied respondants, **21 to 25 years old** and **26 to 30 years old** expressed a moderately high amount of dissatisfaction to their previous job, thus answering our second question, to which that a moderately high number of younger employees resign due to certain dissatisfaction. 

However, the survey suggests that the group of people who express dissatisfaction towards their previous job are those who are in their middle age phase, namely **41 to 55 years old**. This finding suggests a possible lack of satisfaction and recognition were provided to the younger and middle-aged employees.

## Other related findings

![Other related findings](https://github.com/user-attachments/assets/3aa665d1-316d-4ed6-bf2a-87905d0bf240)

By independently analyzing the DETE survey, it is clear that **people making a career switch to private sector** is the main reason why they resign their previous job. While there are no information regarding respondants' age in the DEFE survey, we could hypothesize that many employees who are at a younger age, who are new to the workforce and labor market, AND those relatively older employee who are already establioshed and expereinced in the workforce, have been commonly showing dissatisfaction towards what they were doing, possibly due to lack of satisfaction and recognition, resign their jobs and switch to a different sector for better professional development.

## Content for this project
a) A **"Code"** folder which contains the Python code to execute the analysis for this project

b) A **"Data"** folder which contains the two surveys, DETE and TAFE survey in csv format, as well as all other manipulated dataframes that was produced when performing the analyhis, all in csv format as well

c) An **"Image"** folder which contains all the explanatory charts and statistics in this README page

