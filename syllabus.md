# Syllabus

## General course information ##

Course title: Information and Data Retrieval Systems  
Course number: INFO 4614    
Semester: Fall 2025  
Meeting time: Thursday 2:00pm–3:15pm 
Meeting location: Lucile Berkeley Buchanan Bldg 346  
Instructor: [Kris Shaffer, Ph.D.](https://krisshafferphd.com)  
Instructor email: [kris.shaffer@colorado.edu](mailto:kris.shaffer@colorado.edu)  
Office hours: TBA or by appointment  
Course website: [github.com/kshaffer/cu-info-data-retrieval](https://github.com/kshaffer/cu-info-capstone/)  


### Overview ###

I have been a member or manager of a number of hiring committees for data scientists and data analysts, as well as a senior data scientist at multiple startups. There was one thing that stood out as the largest barrier for those seeking a job or trying to succeed in their job as a data scientist or analyst: a lack of experience working with databases. We turned down some amazing machine learning engineers after wowing us in their interviews because they simply had no experience working with data the way we did on a daily basis, and the job was too senior and the work too demanding for us to teach them those skills on the job. If you want to work with data outside academia, you must know how to work with databases.

More recently, Generative AI has significantly changed the landscape of data science, data analysis, and with them, data engineering and architecture. Many people have experience using the chat interfaces of such tools, and a number of developers have experience using their APIs. However, to build an AI application or integrate more than the most basic AI tools into an existing platform often requires some form of what has come to be known as Retrieval-Augmented Generation (RAG). RAG has introduced a new tool to the world of data operations: the vector database. Though RAG is rapidly changing, all signs point to the vector database being a key part of the data landscape for the foreseeable future, and those with experience working with vector databases will likely have a leg up in the job market.

In this course, you will gain fundamental skills for working with three kinds of databases: relational databases (specifically MySQL), NoSQL databases (MongoDB), and vector databases (Pinecone). You will learn how to create, manage, query, and optimize each type of database, and you will gain experience with the most common tools for working with each. Further, because databases never run on their own, you will interface with all three of these databases from within the Python programming language, the most common production language for data science and data engineering, giving you experience translating data between these database systems and a production-ready Python environment.

### Course description ###

Examines techniques for managing and accessing information and data of a variety of types for a range of applications. Students will study retrieval models for text and for structured and unstructured data, covering creation, management and querying techniques for each, and how to apply each model in data-intensive applications. Students will also consider ethical aspects of data management including data protection, data rights and user privacy.

### Course goals ###

- Understand and apply foundational concepts of information retrieval systems.
- Understand and apply foundational concepts of relational databases, NoSQL databases, and vector databases.
- Create, manage, and query each type of database.
- Know when and why to use each type of database in a research or production environment.
- Manipulate data in each type of database using Python.
- Optimize each type of database for performance and usability.
- Transition data between each type of database and a Python environment, within acceptable limits of data loss.

## Credit and assessment ##

Coursework will be broken into the following five categories (followed by their respective weights for your final grade):

- Daily clicker quizzes: 20%  
- Weekly Colab notebooks: 20%  
- Midterm project 1: 20%  
- Midterm project 2: 20%  
- Final project: 20%  

Daily clicker quizzes will be given at the beginning of each class, and will also sometimes include an "exit ticket" at the end of class. These quizzes are primarily informational for me — letting me know what information from the readings and/or homework you all collectively are the most and least comfortable with. I will use this information to adjust the specific topics and activities of the day and, if necessary, the general pace of the course. They will also double as attendance, and as such, they will only be accepted from people who are physically present in class. They will be graded simply for completion. 

Weekly Colab notebooks will be assigned in order to provide you with familiarity and a bit of digital "muscle memory" around the most important functions and techniques addressed in the course. They will also give you a sense of where tools like AI autocomplete are useful, and where they fall flat on their face. You are welcome, indeed encouraged, to work on these in *pairs* (not in larger groups), provided that each individual submit their own notebook and note who they worked with. These notebooks will be graded for completion, and you will receive feedback on them, but they will not be graded for correctness. 

This course consists of three units covering three different types of information retrieval systems. Each unit will end with a project where you will *individually* create a database of the type covered in that unit and demonstrate your understanding of its workings, utility, and techniques for optimization. Detailed requirements for each of these projects will be provided towards the middle of each unit. They are equal in weight and will be assessed according to the rubric laid out in the project details I provide for each unit.

## Required materials ##

- An account for the class's [Slack](https://slack.com/) channel. (We will set this up during the first day of class.)
- A free [Google Drive](http://drive.google.com) account *using your CU Identikey*.  
- An account for ([Google Colab](https://colab.research.google.com/)). A free account should suffice, but you may want to consider a paid account, if you plan to work with large datasets for your projects.

We will be using CUClickers/iClickers in this class. (The iClicker Student App is available at no cost.) For more information, see
[https://oit.colorado.edu/services/learning-spaces-technology/cuclickers-iclickers](https://oit.colorado.edu/services/learning-spaces-technology/cuclickers-iclickers).

All other required class materials will be posted or linked to on the course GitHub repository. Private (in copyright) materials will be posted in the course's shared Google Drive folder and Slack.

## Policies ##

For instructor and university policies relevant to this course, please see [this page](policies.md).

## About this syllabus ##

This syllabus is a *summary of course objectives and content* and a reminder of *some* relevant university policies, not a contract. *All information in this syllabus (except for the official *course description*) is subject to change, with sufficient advanced notice provided by the instructor.*

In the spirit of collaboration at the center of this course, this syllabus (and the entire course website) is hosted on GitHub, and I will consider pull requests (suggested changes) from students.

