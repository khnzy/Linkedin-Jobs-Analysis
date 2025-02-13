<img width="326" alt="banner" src="https://github.com/user-attachments/assets/7017509b-bf99-4b04-b2e6-4ae09efa3fd5" />

# Linkedin-Jobs-Analysis (Ongoing)

### This is a learning project to handle messy data and perform EDA

## About Data

The LinkedIn data set provided contains 7,927 rows and 15 columns, providing a comprehensive overview of job postings on the platform. The data can be used for data analysis, visualization, and research. The job postings include Data Analyst, Machine Learning Engineer, IT Services and IT Consulting roles, located in various locations around the world, with varying salaries and work hours. The data set includes information about the company, role responsibilities, and required skills for each job. This data set is a valuable resource for understanding job opportunities in different industries and locations.

## Attributes

### Column descriptions
job_ID: Unique identifier for each job posting.

job: The title of the job posting.

location: The location of the job posting.

company_id: The unique identifier for the company offering the job.

company_name: The name of the company offering the job.

work_type: The type of work offered (e.g. full-time, part-time, etc.).

full_time_remote: Indicates if the job is a full-time remote position.

no_of_employ: The number of employees at the company offering the job.

no_of_application: The number of applications received for the job.

posted_day_ago: The number of days ago the job was posted.

alumni: Indicates if the job posting is for alumni of a certain organization.

Hiring_person: The name of the person responsible for hiring for the job.

linkedin_followers: The number of LinkedIn followers of the hiring person.

hiring_person_link: A link to the LinkedIn profile of the hiring person.

job_details: Detailed information about the job, including responsibilities and requirements.
<br><br>

![iss](https://github.com/user-attachments/assets/31f255fd-e586-42a3-a16d-05c38a673169)


<br><br>
## Issue with the data set
Dirty Data:-

Job: column in the data set there is unnecessary information such as the yearly package, technology, company name, and work type (remote), etc added in the title.Consistency
no_of_application: this column has a value that should not be present ('hours', 'minutes'). Consistency
posted_day_ago: In this column, time is added in the form of a string for Exampal (9 hours, 8 minutes). Validity
Alumni: with the alumni count the string is present with the count value ('company alumni'). Validity
company_id: This column is completely blank. Completeness
Hiring_person: In this column, there are some nicknames added within parentheses Consistency
linkedin_followers: In the linkedin_followers column the 'linkedin_followers' string is present with numbers and numbers are separated with (' , ') Validity
Messy Data:-

Full_time_remote: In this column involvement and level are both combined in one column and separated by ('·'). Validity
No_of_employ: In this column employees_count and industry are both combined in one column and the 'employees' string is added extra separated ('·'). Validity
Location: In the location column country, state and city are added in one column and separated by (',') Validity
Job: In the Job column some are starting with the capital letter and some are in small letter Consistency
-company_name: in the company_name also there is inconsistency in the name some of the letters are starting with a small letter and some of them are stares with the capital letter. Consistency
There are 2,084 duplicate values found in the dataset Validity
