
# $${\color{blue}Machine\space\ learning\space\ driven\space\ approach\space\ to\space\ a\space\ comprehensive\space\ career\space\ path}$$ 

## Prepared by:student: 
- Shalini Mishra – 20BCE0763
- Md Tiham Hossain – 20BCE0753
- Pranav Bidve – 20BCE0268
- Annanya Mangla – 20BCE0700


## Table of Contents:bookmark_tabs:
- <i>Problem Statement</i> 
- <i>Motivation</i>
- <i>Novel features</i>
- <i>Challenges Faced</i>
- <i>Workflow diagram</i>
- <i>Project workflow</i>
- <i>Evaluation Metrics</i>
- <i>Project Outcome</i>
- <i>GitHub Readme link</i>

## Problem statement of our project :desktop_computer:
####
In the research paper, "A machine learning approach for future career planning", The user
had to give their current qualifications and the job they are aspiring. After assessing these
details, the machine learning model will provide a path which they need to follow, to reach
their job.
To make this decision easier and timesaving for the user, we can make certain additions like.
The current ranking of universities for a particular degree, the number of scholarships they
would provide, their admission deadlines and criteria. This would make the website a one
stop destination for someone who would want to pursue any career.
An improvisation to the current paper is that we can provide the user with a set of
alumni/employee email ids. This will not only help the user to connect with them but will
also be able to make a prudent decision as to select a particular course, job or even a career
field.
####

## Motivation:handshake:
####
The motivation for this project is to develop a one stop solution for everyone seeking to a
choose a career path. This mainly lies what in what the previous approach was, it just
displayed which path was the best, but it did not tell the user which
universities/offices/location to choose. The collaboration of data with the path gives us a
better stance to take a decision to choose the right path.

####
In the research paper, "A machine learning approach for future career planning", The user had to give their current qualifications and the job they are aspiring. After assessing these details, the machine learning model will provide a path which they need to follow, to reach 
their job. To make this decision easier and timesaving for the user, we can make certain additions like. The current ranking of universities for a particular degree, the number of scholarships they would provide, their admission deadlines and criteria. This would make the website a one stop destination for someone who would want to pursue any career. An improvisation to the current paper is that we can provide the user with a set of alumni/employee email ids. This will not only help the user to connect with them but will also be able to make a prudent decision as to select a particular course, job or even a career 
field.

## Novel features are listed below:bulb:

- Ranking of universities provided in each career path.
- Scholarships provided by each of the universities.
- Admission deadlines of universities.
- Admission requirements for certain colleges.
- Suggestions from Alumni and current employees.

## Workflow Diagram:chart: 
![Blank diagram (2)](https://user-images.githubusercontent.com/87640344/218167970-48f0192d-6d7d-4b32-84fe-469d1ace6fbd.png)


## Project workflow of our Project:white_check_mark:

 | Task | Task description | Timeline | Contribution |
 | --- | --- | --- | --- |
 | Data collection | We aim to collect data from myriad sources like educational institutions, known universities, offices, workplaces and startups. We do this by mailing people working or studying. We will also be contacting the institution or the HR department of a company | Week 0-2 | MD Tiham Hossain |
| Sorting of data  | The data that we aggregate from various resources needs to be sorted based on multiple factors, like the degree that needs to be completed before, or is a prerequisite for the other. Also the data of the universities also needs to be sorted, based on ranking, scholarships and other features. This sorting of data can be done by making use of various algorithms like quick sort or merge sort, depending on which one is more efficient and time saving on our data. | Week 2 | MD Tiham Hossain |
| Data preprocessing | The obtained data from the workplace may not be large enough to represent a big dataset. We need to oversample the data in order to avoid skewing of the result. We try to achieve this by kMeans Smote and SVM Smote | Week 3-5 | Pranav Bidve |
| Categorization of Data | The data that we acquire from the user and from the universities or offices, needs to be categorized, into different streams like Engineering, Medical and Commerce. We categorize the users needs and the external data to ensure accurate mapping. We make use of clustering algorithms, like KNN clustering or BIRCH clustering method to put similar attributes under one category | Week 6 | Pranav Bidve |
| Clustering of data | After gathering a comprehensive dataset having many educational qualifications/degrees, job titles/job posts, we need to group them for better understanding. For example, software development engineer, software developer, programmer all can be grouped as "software engineer". We try accomplish this by using the KNN algorithm. | Week 8 | Shalini Mishra |
| Chain creation | after we have categorized our data, and mapped the users details with that of the universities or offices, next we need to form a chain, which will give a direct path. This path begins from your current position and searches in your category and gives you the path to reach your aspired job. We can make use of features like Markov chaining. This process will provide as many chains or paths as possible to reach your goal. | Week 9 | Shalini Mishra |
| Path prediction | Markov chaining provides various chains that can be followed, out of all these provided chains, the chain which is most suitable and shortest is chosen and displayed to the user. The choosing of the shortest chain is done with the help of bellman Ford algorithm, this algorithm will help us in finding the shortest path among the many paths which we get as output from the chaining process. | Week 10 | Annanya Mangla |
| Displaying output | Finally after the optimal and shortest path is chosen, this path along with the relevant details needs to be displayed in an engaging way to the user, we can display this output in a website which can be integrated with the machine learning and dataset. We can integrate python code with website using flask, and the database can be integrated by making use of mongoDB and nodeJS. The front end of the website can be prepared with the help of ReactJS. | Week 11-12 | Annanya Mangla | 
 
 

# Functional Requirements

### System requirements
| Specifications | Minimum or recommended requirements |
| --- | --- |
| Processor | •	Intel Core i5-9400F Processor onwards <br/> •	AMD Ryzen 5 3500X Processor onwards <br/> •	Minimum Frequency rate should be 1GHz <br/> •	Recommended 2GHz |
| Network | •	Ethernet Connection (LAN) <br/> •	Wireless adapter(Wi-Fi) <br/> |
| Hard Disk | •	Recommended type - HDD <br/> •	Minimum 16GB <br/> •	Recommended 32GB |
|	Memory (RAM) | •	Memory (RAM)|





## Challenges faced:thinking:

####
####
Challenges faced for our project model is procuring and sorting of the erratic data generated by universities and companies. The ever-changing details of each university should be kept abreast. The elicitation of student or employee email ids from the respective sources like institutions, workplaces, and universities can be a conundrum. It would require making a good connection 
with sources.




