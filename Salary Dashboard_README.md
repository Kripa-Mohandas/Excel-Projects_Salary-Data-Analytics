## <B>Excel Project – Yearly Salary Dashboard 

<img width="1795" height="692" alt="Screenshot 2026-09-16 214644" src="https://github.com/user-attachments/assets/9a0e9012-1db0-4226-897d-c83a361b09f6" />

### Introduction
The Yearly Salary Dashboard will help the job seekers to investigate median salaries for the particular job and location. 
 The data set used for this project was real-world data on 2023. The data contains detailed information on job titles, salaries, job location, job type and other essential skills.
 
### Excel Skills Used:
1. Power Query
2. Formulas and Functions
3. Data Validation
4. Charts


### Dashboard Build
 ### Power Query

 I used Power Query to load data and edit the data set.
<img width="432" height="226" alt="Screenshot 2026-09-18 135202" src="https://github.com/user-attachments/assets/731f1ced-de36-4a22-b866-f220b55d0d6b" />

<img width="1907" height="482" alt="image" src="https://github.com/user-attachments/assets/1d4788cd-bb13-4d85-93db-a52670a99c9f" />

Using Power Query, it was very easy to analyze data.

 ### Formulas and Functions

 Calculating Median Salary by Job Title
 
<img width="595" height="162" alt="Screenshot 2026-09-18 140307" src="https://github.com/user-attachments/assets/7ed21934-ce0a-48bd-961b-058e7d63bdb8" />

This formula checks job title, country, job type, excludes blank salaries(ie., only yearly salary) otherwise it shows "Do Data"

Result:
 
<img width="327" height="265" alt="image" src="https://github.com/user-attachments/assets/8da59c0e-7007-466b-955b-31fb10663f4c" />

 ### Data Validation

 Access Job Title from the Job sheet using Data Validation
 
<img width="305" height="378" alt="Screenshot 2026-09-18 141917" src="https://github.com/user-attachments/assets/9c621d78-4bce-434c-9735-ad6fa344b4a6" />

 <img width="697" height="575" alt="Screenshot 2026-09-18 142455" src="https://github.com/user-attachments/assets/0933876a-5050-41e4-bd10-b538ac9654b8" />


Job sheet has following formula to find unique job title in Sort order.

 =SORT(UNIQUE(FILTER(Data[job_title_short],Data[job_title_short]<>"")))
 
<img width="209" height="265" alt="image" src="https://github.com/user-attachments/assets/f7456311-ab81-4f6e-961d-3445421015b7" />


  ### Charts
  Used three charts in this dashboard 
  1. Bar Chart - Job Title with Median Salary
  2. Map Chart - Country Median Salary
  3. Bar Chart - Job Type with Median Salary
     
<img width="2145" height="445" alt="image" src="https://github.com/user-attachments/assets/6da2491c-db36-4ea6-88cc-aa3a8947105f" />

### Conclusion

Based on the above data validation, this dashboard will show the charts, median salary, Job platform posted and its job count.

<img width="2011" height="155" alt="image" src="https://github.com/user-attachments/assets/59b223be-3b48-419f-8ad5-77cd733a08f5" />

This dashboard allows users to make decisions about their career, based on the salary trends, country and job type.

I practiced this from the YouTube channel- Luke Barousse. Thanks Luke.:)
