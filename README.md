# Pewlett_Hackard-Analysis

## Overview of School District Analysis

### Purpose
The purpose of this analysis is to use SQL to assess the retirement-eligbile emoloyee segment from the Pewlett Hackard dataset.  Tables are created to reference employee number and Job Title, as well as distinguish the more recent Job Title gathering To and From Dates for each eligible employee. 

## Results

- The data in retirement_titles.csv suggests that the oldest start dates for retirement eligible employees are actually both Managers who started onm the same date : Jan 1, 1985. 
![Retirement Titles](https://github.com/MoKmo176/Pewlett_Hackard-Analysis/blob/6af2fb0b00f4400009737e3d29b7fed0937878db/README%20Files/Screenshot%202021-10-10%20at%207.18.58%20PM.png)
- The retiring titles count shows a disporportionate amount of Senior level staff to Mid & Entry level. A plan to ensure a smooth transition is most likely. 
![Retiring Titles](https://github.com/MoKmo176/Pewlett_Hackard-Analysis/blob/6af2fb0b00f4400009737e3d29b7fed0937878db/README%20Files/Screenshot%202021-10-10%20at%205.21.50%20PM.png)

- All the duplicate employee numbers in unique_titles.csv require a DISTINCT ON command to reference the most recent status of an eligible employee's title. 

- There are 1,549 eligible employees for Mentorship, some are born in 1965 and have only worked for the company since 2002.

![Mentorship Eligibility](https://github.com/MoKmo176/Pewlett_Hackard-Analysis/blob/6af2fb0b00f4400009737e3d29b7fed0937878db/README%20Files/Screenshot%202021-10-10%20at%207.16.16%20PM.png)

## Analysis Summary

1. There will be 41,380 roles availble if all elgible employees choose to retire. An ideal transition would be to prepare the company from productivity loss, and launch a hiring campaign well in advance. In order to hedge the risk to a 'silver tsunami', allocating resources to employee retention and hiring 20,000 new employees would mitigate the production losses from such an event. 
2. There is an insufficient number of managers and technical leaders to train a large hiring class Senior Staff and Engineers. There is a sufficient amount of Senior Engineers and Senior Staff to hire more Engineers, Assistant Engineers and Staff. By promoting from within and asking Senior level employees to train new hires, a smooth transition can be acheived. The experienced Engineer and Staff employees can quickly fill any vacant roles in Management and Leadership as a new class of Engineers and Staff join Pewlett Hackard, this data is a good primer before allocating hiring resource.


