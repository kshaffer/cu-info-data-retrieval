# Midterm Project 1 - MySQL

The midterm project is designed for you to gain experience, and demonstrate your skills, using MySQL in a real-world scenario. There will be two tracks to this project: 1) database administrator track (DBA) and 2) data analyst track. Choose the one that best suits your interests and/or intended career path.

There will also be two versions of each track: 1) with AI and 2) without AI. I strongly believe that pushing yourself to work _without_ AI will help you become more fluent in SQL, in general. At the same token, working effectively with AI is becoming incredibly important, as well. In fact, it is increasingly uncommon to go into a job interview without being asked about your experience with AI tools. You are free to choose either version. However, do not do so based on what you think will be easier for you. Instead, think about what skills you most need to develop or demonstrate, in light of both your prior experience with SQL (if any) and your long-term goals in information science. 

In all cases, you won't be asked simply to write code or build a database. You will be asked to make a video walkthrough of your working code, showing that it works and explaining the decisions you made along the way. Reasoning and communicating about your work is almost as important as the work itself, and is only growing in importance as AI is being leveraged to do more and more of that work in the wild.

**_Midterm projects will be due Tuesday, September 30, at 2pm._** If you need an extension for any reason other than a university-approved accommodation, please contact me _well in advance._

## DBA Track

### Traditional mode (without AI)

Project: Build a MySQL database from scratch, and demonstrate its functionality.

The project should include the following:

- A MySQL database with at least three tables.
- _The database should be in third normal form._
- All MySQL and/or Python code used to create the database, load in the data, and generate keys and indexes.
- Appropriate use of primary keys, foreign keys, and indexes.
- At least five queries that demonstrate the functionality of the database, including at least one of each of the following:
  - a join
  - at least three aggregate functions (e.g., COUNT, SUM, AVG, MIN, MAX)
  - a common-table expression (CTE)
- A video walkthrough (5 minutes MAX) in which you explain:
  - The purpose of the database
  - The source of the data
  - The design of the database (including an explanation of the tables, keys, and indexes)
  - A demonstration of the functionality of the database (i.e., running the above queries and showing the results)

Note that you should not use any AI tools to generate code or design the database. You may, however, use AI tools to help you understand concepts or troubleshoot issues, as long as you can explain what you learned and how you applied it. _You may also use AI tools to generate dummy data,_ as long as you are not using AI to generate the database schema or SQL code.

Also note that you may use MySQL (insert commands) or Python (pandas.to_sql()) to upload data, but do not use a GUI tool to do so. It is important that you are comfortable adding and processing data in a database using code, in order to be able to work in a production environment in the future.

Upload all code, the video, and any other relevant files (such as CSV files used as data sources) to Canvas by the deadline.

Your grade will be determined by whether or not you accomplished the objectives laid out by the bullet points above (70%), as well as the quality of your explanations and reasoning in the video (30%).

### AI-assisted mode

Project: Build a MySQL database from scratch, and demonstrate its functionality.

The project should include the following:

- A MySQL database with at least three tables.
- _The database should be in third normal form._
- All MySQL and/or Python code used to create the database, load in the data, and generate keys and indexes.
- Appropriate use of primary keys, foreign keys, and indexes.
- At least five queries that demonstrate the functionality of the database, including at least one of each of the following:
  - a join
  - at least three aggregate functions (e.g., COUNT, SUM, AVG, MIN, MAX)
  - a common-table expression (CTE)
- _All prompts_ used to generate code or design the database using AI tools, including prompts that you tried but whose results you discarded.
- A video walkthrough (5 minutes MAX) in which you explain:
  - The purpose of the database
  - The source of the data
  - The design of the database (including an explanation of the tables, keys, and indexes)
  - A demonstration of the functionality of the database (i.e., running the above queries and showing the results)
  - _Explanations of how and why you prompted the AI to create the data and/or code._
  - _Explanations of how you checked and tested the AI's output to ensure accuracy and functionality._

_The most important elements of this project is planning and testing._ Your code may "work," but as we have seen in class, that doesn't mean it's doing what you think it's doing or producing results you expect. The bulk of your time working on this project, and the primary focus of your video, should be on this planning and testing. Knowing how to do this well will help you use AI effectively in the future, but it will also help you be a good project manager or people manager down the line.

Note that you may use MySQL (insert commands) or Python (pandas.to_sql()) to upload data, but do not use a GUI tool to do so. It is important that you are comfortable adding and processing data in a database using code, in order to be able to work in a production environment in the future.

Upload all code, the video, and any other relevant files (such as CSV files used as data sources) to Canvas by the deadline.

Your grade will be determined by whether or not you accomplished the objectives laid out by the bullet points above (70%), as well as the quality of your explanations and reasoning in the video (30%).

## Data Analyst Track

### Traditional mode (without AI)

Use one of the following SQL dump files to create a local copy of a MySQL database:

- [Needledrop database](midterm_files_mysql/needledrop_music_store.sql) (fictional digital media store)
- [Adsphere database](midterm_files_mysql/adsphere_social_ads.sql) (fictional social media ad platform)

Then create a Colab/Jupyter notebook that connects to the database and uses SQL queries to answer analytical questions that you formulate. Think like a curious analyst or researcher, and be sure that your notebook tells a story about the data.

Your notebook should include the following:

- A connection to the MySQL database.
- At least 10 SQL queries that answer analytical questions about the data. Be sure to include multiple examples of each of the following:
  - inner join
  - left join
  - union or union all or intersect
  - at least three different aggregate functions (e.g., COUNT, SUM, AVG, MIN, MAX)
  - a common-table expression (CTE)
- Data visualizations (using matplotlib, seaborn, plotly, d3graph, or another Python visualization library)
- In place of one or more visualizations, you may also include NLP functionality (e.g., sentiment analysis, topic modeling, entity extraction, a Word2Vec model, etc.) if appropriate to your analysis.

Note that you should not use any AI tools to generate code. You may, however, use AI tools to help you understand concepts or troubleshoot issues, as long as you can explain what you learned and how you applied it.
- A video walkthrough (5 minutes MAX) in which you explain:
  - Your basic understanding of the data (e.g., what the tables represent, how they are related, etc.)
  - The questions you sought to answer
  - A demonstration of your code and visualizations (i.e., running the above queries and showing the results)
  - An explanation of your key findings as an analyst/researcher
  
Upload all code, the video, and any other relevant files to Canvas by the deadline.

Your grade will be determined by whether or not you accomplished the objectives laid out by the bullet points above (70%), as well as the quality of your explanations and reasoning in the video (30%).

### AI-assisted mode

Use one of the following SQL dump files to create a local copy of a MySQL database:

- [Needledrop database](midterm_files_mysql/needledrop_music_store.sql) (fictional digital media store)
- [Adsphere database](midterm_files_mysql/adsphere_social_ads.sql) (fictional social media ad platform)

Then create a Colab/Jupyter notebook that connects to the database and uses SQL queries to answer analytical questions that you formulate. Think like a curious analyst or researcher, and be sure that your notebook tells a story about the data.

Your notebook should include the following:

- A connection to the MySQL database.
- At least 10 SQL queries that answer analytical questions about the data. Be sure to include multiple examples of each of the following:
  - inner join
  - left join
  - union or union all or intersect
  - at least three different aggregate functions (e.g., COUNT, SUM, AVG, MIN, MAX)
  - a common-table expression (CTE)
- Data visualizations (using matplotlib, seaborn, plotly, d3graph, or another Python visualization library)
- In place of one or more visualizations, you may also include NLP functionality (e.g., sentiment analysis, topic modeling, entity extraction, a Word2Vec model, etc.) if appropriate to your analysis.
- Text explanations of your analytical questions and findings (anything from a good caption for each visualization to one or more paragraph-length "answers" to the research questions; there is no need to write a full report, but you can if you like).
- _All prompts_ used to generate code or structure the narrative using AI tools, including prompts that you tried but whose results you discarded.
- A video walkthrough (5 minutes MAX) in which you explain:
  - Your basic understanding of the data (e.g., what the tables represent, how they are related, etc.)
  - The questions you sought to answer
  - A demonstration of your code and visualizations (i.e., running the above queries and showing the results)
  - An explanation of your key findings as an analyst/researcher
- _Explanations of how and why you prompted the AI to create the code/notebook._
- _Explanations of how you checked and tested the AI's output to ensure accuracy and functionality._

_The most important elements of this project is planning and testing._ Your code may "work," but as we have seen in class, that doesn't mean it's doing what you think it's doing or producing results you expect. Also, when it comes to analysis, AI often fails to get at the heart of the matter, or to connect individual components into a good story. The bulk of your time working on this project, and the primary focus of your video, should be on this planning and testing. In particular, I anticipate that you will have to do a lot of iteration, perhaps even some "negotiation," with the AI in order to get a coherent analytical story. _You will likely get more frustrated with the AI than your DBA-track colleagues._ However, ths back-and-forth with the AI may actually help you craft a more coherent narrative than your non-AI analyst colleagues, as well as develop your analytical thinking and storytelling skills.
  
Upload all code, the video, and any other relevant files to Canvas by the deadline.

Your grade will be determined by whether or not you accomplished the objectives laid out by the bullet points above (70%), as well as the quality of your explanations and reasoning in the video (30%).
