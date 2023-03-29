
# $${\color{red}Machine\space\ learning\space\ driven\space\ approach\space\ to\space\ a\space\ comprehensive\space\ career\space\ path}$$ 

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
The motivation for a research work titled "A machine learning-driven approach for comprehensive career path" could stem from several reasons. One possible reason is that individuals often struggle with finding the right career path and may not have access to personalized career advice. Traditional career guidance often involves self-assessment and advice from career counselors, but this process can be time-consuming and may not result in the best career fit.
Machine learning techniques have the potential to provide a more efficient and personalized approach to career guidance. By analyzing large amounts of data on job requirements, job satisfaction, and individual preferences, a machine learning-driven approach could identify potential career paths and make personalized recommendations to individuals.Furthermore, this research work could also help organizations in career development and succession planning for their employees. By using machine learning algorithms to analyze employee data, such as job performance, career interests, and skillsets, organizations could identify potential career paths and make recommendations for training and development opportunities to help employees reach their career goals within the organization.

Overall, a machine learning-driven approach for comprehensive career path has the potential to provide individuals and organizations with a more efficient and personalized approach to career development, making it a worthwhile area of research.

## Novel features are listed below:bulb:

- Ranking of universities provided in each career path.
- Scholarships provided by each of the universities.
- Admission deadlines of universities.
- Admission requirements for certain colleges.
- Suggestions from Alumni and current employees.

## Literature Review

|Sr. No |Paper name|Year of publication|Work Done|Gaps found|
| --- | --- | --- | --- | --- |
|1|Career Path Prediction and Counseling with Machine Learning|2019|The authors developed a career path prediction and counseling system using machine learning that considers a user's education level, work experience, and job preferences|The accuracy of the system may be limited by the quality and completeness of the user data and the lack of data on alternative career paths|
|2|An Optimization Model of Applied Career Planning for Innovative and Entrepreneurial Talents Based on Credible Neural Networks|2022|The best career goals are determined in accordance with their own careers by thoroughly analyzing and weighing their own interests, hobbies, abilities, and characteristics in light of their own career’s subjective and objective conditions, as well as by measuring, analyzing, and summarizing those conditions|we should actively advocate the cooperative development of courses by industry and enterprises, promote the effective connection between the curriculum content and the demands of professional posts, this causes a lot of intricacy in the task|
|3|Intelligent Career Planning System based on Machine Learning and Ontology|2019|The authors developed an intelligent career planning system based on machine learning and ontology that considers a user's interests, skills, and job requirements|The system's accuracy may be limited by the quality and completeness of the user data and the lack of data on alternative career paths|
|4|A Deep Learning Approach to Predict Career Transitions|2018|The authors used deep learning techniques to predict career transitions based on a dataset of job transitions and social network data|More research is needed to validate the accuracy of the approach and to better understand the factors that contribute to career transitions|
|5|A Comparative Study of Machine Learning Algorithms for Career Prediction|2020|The authors compared several machine learning algorithms for predicting future careers using a dataset of student profiles and their chosen careers.|More research is needed to evaluate the generalizability of these algorithms to different populations and to better understand the factors that influence career choice.|
|6|CareerPath: A Machine Learning Based Career Planning System|2018|The authors developed a machine learning-based career planning system using a dataset of job descriptions and skills required to recommend careers based on a user's skills and interests.|The system's accuracy may be limited by the quality and completeness of the data used to train the model.|
|7|Predicting Career Success via Supervised Machine Learning|2019|The authors used supervised machine learning to predict career success based on several factors, including education, work experience, and personality traits.|More research is needed to determine the factors that contribute to career success and to validate the accuracy of the model.|
|8|Intelligent Career Planning System based on Machine Learning and Ontology|2019|The authors developed an intelligent career planning system based on machine learning and ontology that considers a user's interests, skills, and job requirements.|The system's accuracy may be limited by the quality and completeness of the user data and the lack of data on alternative career paths.|
|9|A Hybrid Machine Learning Approach for Career Path Prediction and Planning|2021|The authors developed a hybrid machine learning approach for career path prediction and planning that combines clustering and classification algorithms.|The authors found that the accuracy of the system may be limited by the quality and completeness of the user data and the lack of data on alternative career paths.|


## Workflow Diagram:chart: 
![Blank diagram (2)](https://user-images.githubusercontent.com/87640344/218167970-48f0192d-6d7d-4b32-84fe-469d1ace6fbd.png)


## Project workflow of our Project:white_check_mark:

 | Task | Timeline | Contribution |
 | --- | --- | --- |
 | Data collection | Week 0-2 | Md Tiham Hossain |
| Sorting of data  | Week 2 | Md Tiham Hossain |
| Data preprocessing | Week 3-5 | Pranav Bidve |
| Categorization of Data | Week 6 | Pranav Bidve |
| Clustering of data | Week 8 | Shalini Mishra |
| Chain creation | Week 9 | Shalini Mishra |
| Path prediction | Week 10 | Annanya Mangla |
| Displaying output | Week 11-12 | Annanya Mangla | 
 
 
## Data collection: 

We aim to collect data from myriad sources like educational institutions, known universities, offices, workplaces, and startups. We do this by mailing people working or studying. We will also be contacting the institution or the HR department of a company. In addition to all these data, we will be taking the linkedIn dataset, which holds the entire details of people’s current job profile and their future goal.

### Dataset link: https://www.kaggle.com/datasets/stackoverflow/stack-overflow-2018-developer-survey
The data belongs to a kaggle survey, we slectedthis datset because of its varied number of columns, prefrences and easy work flow.

## Sorting of data:

The data that we aggregate from various resources needs to be sorted based on multiple factors, like the degree that needs to be completed before, or is a prerequisite for the other. Also the data of the universities also needs to be sorted, based on ranking, scholarships and other features. This sorting of data can be done by making use of various algorithms like quick sort or merge sort, depending on which one is more efficient and time saving on our data.

## Data preprocessing:

The obtained data from the workplace may not be large enough to represent a big dataset. We need to oversample the data in order to avoid skewing of the result. We try to achieve this by kMeans Smote and SVM Smote.

## Categorization of Data:

The data that we acquire from the user and from the universities or offices, needs to be categorized, into different streams like Engineering, Medical and Commerce. We categorize the users’ needs and the external data to ensure accurate mapping. We make use of clustering algorithms, like KNN clustering or BIRCH clustering method to put similar attributes under one category

## Clustering of data:

After gathering a comprehensive dataset having many educational qualifications/degrees, job titles/job posts, we need to group them for better understanding. For example, software development engineer, software developer, programmer all can be grouped as "software engineer". We try accomplishing this by using the KNN algorithm.

## Chain creation:

after we have categorized our data, and mapped the users details with that of the universities or offices, next we need to form a chain, which will give a direct path. This path begins from your current position and searches in your category and gives you the path to reach your aspired job. We can make use of features like Markov chaining. This process will provide as many chains or paths as possible to reach your goal.

## Path prediction:

Markov chaining provides various chains that can be followed, out of all these provided chains, the chain which is most suitable and shortest is chosen and displayed to the user. The choosing of the shortest chain is done with the help of bellman Ford algorithm, this algorithm will help us in finding the shortest path among the many paths which we get as output from the chaining process.

## Displaying output:

Finally, after the optimal and shortest path is chosen, this path along with the relevant details needs to be displayed in an engaging way to the user, we can display this output in a website which can be integrated with the machine learning and dataset. We can integrate python code with website using flask, and the database can be integrated by making use of mongoDB and NodeJS. The front end of the website can be prepared with the help of ReactJS.


 

# Functional Requirements:writing_hand:

### System requirements
| Specifications | Minimum or recommended requirements |
| --- | --- |
| Processor | •	Intel Core i5-9400F Processor onwards <br/> •	AMD Ryzen 5 3500X Processor onwards <br/> •	Minimum Frequency rate should be 1GHz <br/> •	Recommended 2GHz |
| Network | •	Ethernet Connection (LAN) <br/> •	Wireless adapter(Wi-Fi) <br/> |
| Hard Disk | •	Recommended type - HDD <br/> •	Minimum 16GB <br/> •	Recommended 32GB |
|	Memory (RAM) | •	Memory (RAM)|


### Tools/Software Used

| SPecifications | Requirements |
| --- | --- |
| Operating System | •	Windows – 7 or newer </br> •	MAC – OS X v10.7 or newer </br> •	 Ubuntu - 17.04 |
| Python | •	Anaconda </br> •	Jupyter Notebook |
| Database | •	MySql |
| Framework | •	Flask |


## Evaluation Metrics:fountain_pen:
In the research paper "A machine learning approach for future planning", an algorithm is devised which gives the most optimal chain to choose the correct career path based on the current qualifications and aspiring job, but this paper does not provide guidance on how each of these steps are to be followed, the user of the algorithm will have to collect information from different websites to clear their doubts.
The algorithm devised in this study gives the users a one stop destination, after which the users will not have to search for further information about degree requirements, college rankings, scholarships, and fees.
This will ease the process of future planning and will create a proper guide for the users. 


## Challenges faced:thinking:

####
####
Challenges faced for our project model is procuring and sorting of the erratic data generated by universities and companies. The ever-changing details of each university should be kept abreast. The elicitation of student or employee email ids from the respective sources like institutions, workplaces, and universities can be a conundrum. It would require making a good connection 
with sources.

## References:books:

[1] Chen, T., Liu, Y., Gao, Y., Yang, J., & Wang, B. (2019). Career path prediction and counseling with machine learning. In 2019 18th International Symposium on Distributed Computing and Applications for Business Engineering and Science (DCABES) (pp. 163-167).<br>
[2] Li J( 1 ), Wang X( 2 ). An Optimization Model of Applied Career Planning for Innovative and Entrepreneurial Talents Based on Credible Neural Networks. Security and Communication Networks. 2022;2022. doi:10.1155/2022/3580803.<br>
[3] Wei, B., Liao, M., Huang, J., & Tang, X. (2019). Intelligent career planning system based on machine learning and ontology. In 2019 14th IEEE Conference on Industrial Electronics and Applications (ICIEA) (pp. 2509-2514).<br>
[4]  Lai, J. H., Lin, Y. C., & Huang, Y. Y. (2018). A deep learning approach to predict career transitions. In 2018 IEEE International Conference on Big Data (Big Data) (pp. 3900-3907).<br>
[5] Wu, Z., Liu, L., Li, Y., & Yang, Z. (2020). A comparative study of machine learning algorithms for career prediction. Journal of Information Science and Engineering, 36(3), 689-700.<br>
[6] Liu, X., Yang, X., Tang, Y., Zhang, X., & Wang, B. (2018). CareerPath: A machine learning based career planning system. In 2018 IEEE International Conference on Big Data (Big Data) (pp. 4089-4094).<br>
[7] Bartlett, J. E., Bartlett, M. E., & O'Connor, K. E. (2019). Predicting career success via supervised machine learning. Journal of Career Assessment, 27(4), 658-671.<br>
[8] Wei, B., Liao, M., Huang, J., & Tang, X. (2019). Intelligent career planning system based on machine learning and ontology. In 2019 14th IEEE Conference on Industrial Electronics and Applications (ICIEA) (pp. 2509-2514).<br>
[9] Wang, W., Zou, Y., Wu, C., & Xie, K. (2021). A hybrid machine learning approach for career path prediction and planning. IEEE Access, 9, 50633-50642.<br>


