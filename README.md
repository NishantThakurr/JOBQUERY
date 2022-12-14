# JOBQUERY



Ever wondered about Data Science jobs in India?Well here is your solution.

An interactive Power BI dashboard which provides indepth analysis of Data Science jobs in India.It takes job role and type of job you want as an input and delivers various variables such as top skills,companies/locations with most available openings and various levels of experience.




## 🚀 About Me
I am Nishant Thakur who is passionate about data and constantly learning about the various field of data science.

## Demo
You can directly access the dashboard here.
https://www.novypro.com/project/jobqueryindiadatascience

https://user-images.githubusercontent.com/102639991/187210384-62ec4c33-4c6e-43a6-a9fd-00fa73285aa8.mp4


## Screenshots

![Screenshot (330)](https://user-images.githubusercontent.com/102639991/186885660-3735f233-3177-4631-8b4d-cd99e700f900.png)
![Screenshot (326)](https://user-images.githubusercontent.com/102639991/186885664-9d49ee8a-9fa8-492b-bed5-9fe8a1f9bdfb.png)
![Screenshot (328)](https://user-images.githubusercontent.com/102639991/186885668-ea4d0c98-f432-4285-96b9-716e6d40ff95.png)


## Roadmap

1)Gathering the data

The dataset was downloaded from kaggle.
https://www.kaggle.com/datasets/anandhuh/data-science-jobs-in-india

2)Exploring/Cleaning data and feature engineering.

•Python pandas and numpy were mainly used to explore the data with a little help of our friend Excel.
There were several same job roles written in different format.So by creating a function they were grouped into most relevant job roles.
![image](https://user-images.githubusercontent.com/102639991/187209572-c5902251-9d4d-4626-ae46-75c7571d06ae.png)

•Location column was also cleaned.
![image](https://user-images.githubusercontent.com/102639991/187209950-eea210e3-a399-43fb-a122-74b5123a4a4c.png)
•A separate column was generated for categorizing the type of job into remote or onsite

•Many irrelevant values was also removed from Job experience column and min experience required column was fetched.


![image](https://user-images.githubusercontent.com/102639991/187210089-f937158c-874a-4182-8e82-9ee6ed5158bf.png)

•Working with skills column was tricky had to create a new dataframe using FreqDist.

![image](https://user-images.githubusercontent.com/102639991/187210231-9e0b4354-9029-4764-8dd3-f8618116c5d5.png)
•The two dataframe were then saved into two separate xlsx files

3)Working with PowerBI

The two xlsx files were then loaded into PowerBI and various process were done to form a dashboard such as 
•Data Modelling
•Transform data
•Add Column(to convert min. experience required into categories)
•Dashboard Tiles






## 🛠 Skills
Basic Excel,Python,Power BI

