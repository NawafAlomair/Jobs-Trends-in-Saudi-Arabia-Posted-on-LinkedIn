<h1># Jobs-Trends-in-Saudi-Arabia-Posted-on-LinkedIn</h1>

<h3>Problem statement:</h3>
The manual search for a suitable job based on the education degree, position jobs, years of seeker experience, and the preferred industries can be time-consuming and prone to getting a not stable job. To this end, computer-based methods offer an exciting solution to support job seekers. In this regard, we suggest a recommendation system based on job seekers' pieces of information through our analysis of job data spread in the most popular platform LinkedIn, where the job seeker meets the employer.


<h3>Goal:</h3>
Helping the job seeker to search efficiently and effectively for suitable jobs for him, and the career and academic level most in demand in the labor market. The job seeker also knows the various companies in Saudi Arabia.

<h3>Jobs in 2030 vision:</h3>
The “Kingdom’s Vision 2030” has made several achievements in the field of jobs, including localization agreements, and contributed to reducing unemployment and creating thousands of new job opportunities. also created and innovation was supported by supporting small and medium enterprises, in addition to raising the participation of Saudi women in the workforce.



<h3>Dateset & Preprocessing:</h3>
The dataset we used about Saudi Arabia jobs in 2020 which posted on the LinkedIn platform. It contains 48443 rows and 10 columns which are: 
linkedin_id            
date
 job_functions        
 industries
description
 position_id
 position
 company
 location
 level 

<h3>EDA & Dashboard:</h3>

1- THE DISTRIBUTION OF JOB POSITIONS IN THE SAUDI ARABIA REGIONS
![image](https://user-images.githubusercontent.com/74193850/202890975-a92cd505-7662-4554-a1e0-f816dc3c3fb8.png)

2-DISTRIBUTION OF THE TOTAL JOB VACANCIES ANNOUNCED IN EACH MONTH FOR THE TOP FIVE REGIONS WITH VACANCIES JOB
![image](https://user-images.githubusercontent.com/74193850/202890996-8279f969-faa5-48c4-8b70-3d83e9eb6f6d.png)

3- THE DISTRIBUTION OF REQUIRED LEVELS OF JOBS IN 2020
![image](https://user-images.githubusercontent.com/74193850/202891016-295d8eaa-cf61-48e6-ae4a-5bbfa5a35f37.png)

<h3>Conclusion:</h3>
In this project, we used the jobs positions dataset posted on the LinkedIn platform collected in 2020. We cleaned data and applied multiple processed techniques to prepare the dataset for modeling. 
In the first approach, we created several Machine Learning classifications and we got the best result after solving the overfitting and Resample dataset by using XGBClassifier.
In the second approach, we created a recommendation system that takes the job’s title and returns recommended jobs position based on its description.
In conclusion, because of the nature of our dataset, we got better results by using a recommendation system than classification models.



<h3>Future work:</h3>
We can extract the job positions by ourselves using tools, and that gives us the option to extract more information better, like gender and what salary expects.
Apply deployment for the project.
We can extract data from other resources.



