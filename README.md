# E_clean_AI
Emails are the MOST important communication in any organizations or schools or industries.  Influx of messages every day in millions to various users such as Doctors, Engineers, Managers and students can waste THEIR AND PUBLIC time if they are not  prioritized or not ranked

Problem Statement

Creating clean and green email communication for professionals like managers, scientists, engineers, and doctors is important. Optimizing email visualization using smart AI algorithms can significantly enhance email communication's efficiency and environmental impact. 
Motivation for the Project: Clean and Green Singapore. https://www.cgs.gov.sg/. The requirements of this project were provided by  David Woon, from Continental Automotive Singapore. 

Proposed solution:
1.	Data Collection and Labeling:
•	A significantly large and diverse dataset of emails from enron (Reference 1) is considered for training AI models. The dataset was modified based on the person, who suggested the project. The modification is provided in preparatory.ipynb
•	First, a dataset (smartcontinental.csv) of 9571 observations was obtained from an enormously large dataset. These emails are labelled according to specified categories (time_waste, reply, required_response). 
•	Next, a dataset (email_details.csv) of 4521 observations was obtained to understand the body of the email and its contents are studied and summarized for insights. 
2.	Priority Ranking:
•	Develop a priority ranking algorithm that takes into account the labels assigned to each email (time_waste, reply, required_response) and any additional factors like sender importance or email urgency.
3.	Recommendation System:
•	Implement a recommendation system that suggests actions based on the priority ranking. For example, if an email is classified as "required_response," the system could recommend replying promptly.
4.	Natural Language Understanding (NLU):
•	To understand the content of emails, NLU techniques, such as sentiment analysis, entity recognition, and topic modelling is considered. This can provide insights into the email's content.
By considering these points, we can ensure that the email response recommendation and classification system is robust, customizable, and capable of meeting the specific needs of different organizations and users.



Reference 1: The Enron Email Dataset | Kaggle
