# Midterm Project 2 - MongoDB

The midterm project is designed for you to gain experience, and demonstrate your skills, using MongoDBand Pymongo in a real-world scenario: building a fully functioning social-media scraper in Python that uses MongoDB and Pymongo to store the data and support analytical findings. 

There will be no separate tracks this time, but everyone will do a mix of backend and analysis, with limited but required AI assistance. We have been building towards this project with our in-class work and homework. Between that work and your Python/Pandas work in previous courses, you should already have most of the code you need to complete this project — just copy, paste, and tweak. The challenges will be in planning, assembling those pieces into a coherent whole, and testing the functionality. Those are the areas I will expect (or require) you to use AI.

Like Midterm 1, you won't be asked simply to write code or build a database. You will be asked to make a video walkthrough of your working code, showing that it works and explaining the decisions you made along the way. Reasoning and communicating about your work is almost as important as the work itself, and is only growing in importance as AI is being leveraged to do more and more of that work in the wild.

**_Midterm projects will be due Tuesday, November 18, at 2pm._** If you need an extension for any reason other than a university-approved accommodation, please contact me _well in advance._


## Assignment requirements

Project: Build a social-media scraper in Python, store the post data in a local MongoDB instance, use Pymongo to access the data from a Jupyter notebook, and leverage Python tools like Pandas, matplotlib, seaborn, plotly, or your other favorite tools to perform analysis and make visualizations that communicate insights from your data. Use AI to test its functionality and the completeness of the assignment. Then make a 5-minute-max video demonstrating its functionality and explaining your main analytical findings.

The project should include the following.

### Features

(each is worth one point unless stated otherwise)

- All code in a single Jupyter notebook, with output showing. (One exception: if you need to re-run the notebook, but already have your posts scraped, you can skip that step. Just be sure that I can see the number of posts in your database.)
- Python code that scrapes data from a social media platform of your choice (100% fine to stick to Mastodon, but you have the freedom to scrape others if you want) _via automation_ (i.e., you press go, and it scrapes 10,000 posts, _not_ you press go 250 times and get 40 new posts each time).
- A MongoDB database with at least 10,000 posts in it.
- Python code that creates that database and the posts collection inside it.
- At least one text index, for the main content field (to enable keyword/phrase searching).
- At least two other indexes (single-field or compound) _that you search against in your analysis_ — dates, usernames, follower counts, hashtag names, whatever you are performing your analysis on. (2 points - one per index)
- A count of the posts in the database
- The top users in the database (by post count, follower count, or some other metric from the data — with code that prevents duplicate users)
- The top hashtags, links, or other similar feature in the collection
- A keyword search (i.e., searching for words or phrases _within_ the text content of the post, user bio, etc.)
- At least three aggregation pipelines that use \$unwind and/or \$group in addition to other functions (these pipelines can do double-duty, accomplishing other bullet points with the same code) (three points)
- At least one use of counting accumulators (sum, avg, min, max, etc.)
- At least two uses of MongoDB filters (gt, lt, gte, lte, ne, exists, etc.) (two points)
- An example of bringing a "deep" field up to the top level of the hierarchy
- At least five different visualizations of at least three different types — line chart, bar chart, box-and-whisker plot, stacked bar chart, scatter plot, etc. PIE CHARTS AND DONUT CHARTS DO NOT COUNT (three points)

The above will count for 70% of your project grade. (# of requirements met / 20 * 0.7)

### AI Testing

(each is worth one point unless stated otherwise)

- Upload your notebook AND THIS ASSIGNMENT RUBRIC to an AI platform and ask it to identify any assignment requirements that are not met BY WORKING CODE WITH DISPLAYED OUTPUT in your notebook. Providing it the answer keys to our in-class notebooks would also be helpful to guide the testing process, so it knows what you've done and what is expected from your project, and can point you to specific examples in that code that can guide you. 
- Address any missing or non-functional elements in your project and repeat the test.
- Include a document (preferably a PDF of your AI chat) that contains the entirety of your conversation (_all prompts_ used and _all AI responses_) for this testing process.
- AI should generally _not_ be writing code for you — you already have the building blocks in your in-class notebooks and my provided keys. However, it may be helpful for debugging, getting you out of jams, brainstorming the analytical process, planning ways to make sure you are fulfilling the requirements, and directing your attention to relevant examples in the in-class notebooks. If you use it for any of these purposes, include a PDF showing the entirety of those discussions.

The above will count for 10% of your project grade. (# of requirements met / 3 or 4 * 0.1)


### Video walkthrough

5 minutes MAX, in which you explain (one point each):

- Your basic understanding of the data
- How and why you created the specific indexes you created
- The questions you sought to answer
- A demonstration of your code and visualizations (i.e., running _a few_ of the above queries and showing the results)
- An explanation of your key findings as an analyst/researcher
- _Explanations of how you used AI to plan, assist, and/or test your scraper and analysis._

The above will count for 20% of your project grade. (# of requirements met / 6 * 0.2)


## Completion and assessment

Upload all code, the video, AI chat logs, and any other relevant files to Canvas by the deadline.

Your grade will be determined by whether or not you accomplished the objectives laid out by the bullet points above (70%), the quality of your AI-assisted testing (10%), and the quality of your explanations and reasoning in the video (20%).