# Track My Job Apply

## Introduction.   
In my opinion, it is necessary to develop an application that can track the status of job applications. With a highly competitive society, many people submit their resumes to hundreds of companies in order to find a job. In view of the current situation, candidates can learn about their application status mainly through two ways: receiving an email from the company that tells them whether to enter the next round of interviews, and logging in to the recruitment interface of each company to check the status. However, the time for applicants to submit resumes is different. Even if the application time is the same, the time for the company to reply or update the application status is different. Due to the large number of applied companies and the long period of job apply, applicants may not be able to fully remember the application status of all companies. It is especially important to develop a website that can check the status of all job applications to help applicants have real-time information. This website is called “TrackMyJobApply”.    
Take me as an example. In order to be a summer intern in 2020, I began to submit resumes to various companies since last November. The positions to be applied are mainly business analysts and data analysts, as well as a few financial analysts. The company's fields are also diverse, including technology, finance, real estate, consulting and so on. A month later, I have forgotten which companies I applied for, let alone know the application status of each company. However, TrackMyJobApply’s website helps applicants update their application status in real time. The website synchronizes the information after the applicant has applied for a job. After a while, I hope to check the status of previous applications. I just need to log in to TrackMyJobApply’s website, instead of logging in to the recruitment official website of each company or checking my own historical email.    
TrackMyJobApply’s website has a database that collects information about users applying for jobs. The database will store the job name, the application time, and the real-time status. At present, the database may not contain enough information. But as I learn more, I will further improve of the database.
    
## TrackMyJobApply Use Cases
Creating an Account Use Case
The first use case about this database is for users to create an account on the website.
1.	The user first opens the website page.
2.	The user clicks "Need an Account" or "Sign in"
3.	When creating an account, users need to enter their name, phone number, email address and set a password.
4.	Install Internet tracking software so that the system can automatically track pages when users apply for jobs.
    
Tracking Job Application Use Case
In the second use case, the website tracks the job application of users and extract important information into the database.
1.	Open network tracking software.
2.	Click on the website of job that you want to apply for.
3.	The website automatically tracks the pages where users apply for jobs and extracts important data.
    
Checking Application Use Case
The core purpose of the website to integrate job application information is to provide convenience for users to check the status later.
1.	User opens website and logs into created account.
2.	The user enters a keyword or selects the range of information.
3.	Click on "search".
4.	The website will display all historical application records that the user needs.
5.	If the user wants to focus on some application status, click "Favorite".
6.	If the user wants to share the application link to others, click "Share".

## Business Rules for My Database
    •	Each apply is associated with one account.
      Each account may be associated with many applications.
    •	Each apply must be associated with a job.
      A job is associated with one to many applications.
    •	Each apply must be associated with one company.
      A company must be associated with many applications.
    •	Each job is associated with one company.
      One company must have one or many job vacancies.
    •	An account is a free account or a paid account. 
    •	A job is an internship, full-time job, and part-time job. 
    •	Each job must have one address. One address may have many jobs.
