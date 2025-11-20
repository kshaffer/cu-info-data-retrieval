# Final Project - RAG Application and Vector Databases

The final project is designed for you to gain experience, and demonstrate your skills, using MongoDB, Pymongo, Ollama, and vector operations in a real-world scenario: building a fully functioning AI chatbot that leverages custom data. 

There will be no separate tracks this time, but everyone will do a mix of backend and analysis, with limited but required AI assistance. We have been building towards this project with our in-class work and homework. You should already have all of the code you need to complete this project — just copy, paste, and tweak. We have also walked through planning and assembling those pieces into a coherent whole. Your main work here is to ensure, adn demonstrate, that you know how those pieces work, put them into operation on a dataset you care about, and then test the functionality to ensure it works as intended. _Testing is the only area in which I expect you to use AI for this project._

Like the midterm projects, you won't be asked simply to write code or build a database. You will be asked to make a video walkthrough of your working code, showing that it works and explaining the decisions you made along the way. Reasoning and communicating about your work is almost as important as the work itself, and is only growing in importance as AI is being leveraged to do more and more of that work in the wild.

**_Final projects will be due Wednesday, December 10, at 4pm._** (This is the end of the assigned exam slot for our class.) Only extensions that conform with university-approved accommodations will be accepted.

## Project requirements

Project: Build an AI chatbot that leverages a vector database in a RAG (Retrieval-Augmented Generation) pipeline to answer user questions according to custom data that you provide. (It can run in a Jupyter notebook, but it's worth taking a stab at making it run in the terminal, if you have experience with that.) Tokenize your data by sentence using NLTK, generate sentence embeddings using sentence_transformers (and a sentence model of your choosing), store the data and embeddings in a MongoDB database with a vector embedding index, use a similarity algorithm (cosine similarity is fine, in fact, preferred) to find sentences relevant to your question, build a prompt constructor that sends the user question, database search results, and instructions to Ollama, and print the resulting Ollama output to the user. Use AI to test its functionality and the completeness of the assignment. Then make a 5-minute-max video demonstrating its functionality and explaining your main analytical findings.

A couple ideas:

- Use the complete works of an author from [Project Gutenberg](https://gutenberg.org) to generate a chatbot that mimics different characters. Or helps actors speak like them. Or helps students study for a literature exam.
- Use a multilingual model to answer questions in English about texts in another language (like the works of Plato in Greek, or Newton in Latin, or Tolstoy in Russian).
- Use articles from major newspapers about a specific part of the world to answer questions about history, culture, and current events for a diplomat in training.

There are tons of possibilities. And this is the biggest decision you have to make in the project, as well as the thing that will make it most interesting. So put some good thought into it before you get too far!

Whatever topic you choose, the project should include the following.

### Features

(each is worth one point unless stated otherwise)

- All code in a single Jupyter notebook, with output showing. (One exception: if you need to re-run the notebook, but already have your content loaded and indexed, you can skip that step. Just be sure that I can see the number of posts in your database and evidence of the indexes.)
- Python code that loads in a _significant_ chunk of text data. (I'm being vague here, as the amount depends on the project, but we're talking like _the complete works of Shakespeare_ or a couple hundred articles on a particular topic from the New York Times. A similar scope to the MongoDB midterm — at least 10,000 sentences, but make the boundaries of your collection make sense.)
- Python code that tokenizes that content by sentence using NLTK.
- Python code that uses sentence_transformers to generate an embedding for each sentence.
- A MongoDB database storing the sentences, text, and any metadata you care about (the title of the novel, the date of the article, etc.).
- Python code that creates that database and the posts collection inside it.
- A vector index applied across the embeddings.
- A count of the documents in the database.
- Python code that accepts a user question and generates an embedding for that question using the same model as the database content.
- Python code that performs a similarity search for that question's embedding across the _indexed_ vector database and returns an appropriate number of hits.
- Python code that constructs an Ollama prompt from 1) the question, 2) the vector search results, and 3) custom instructions you have honed in testing with your chatbot goal in mind.
- Python code that sends the prompt to Ollama, using an appropriate model for your task, and returns the answer to the user's question.

The above will count for 70% of your project grade. (# of requirements met / 12 * 0.7)

### AI Testing

(each is worth one point unless stated otherwise)

- Upload your notebook AND THIS ASSIGNMENT RUBRIC to an AI platform and ask it to identify any assignment requirements that are not met BY WORKING CODE WITH DISPLAYED OUTPUT in your notebook. Providing it the answer keys to our in-class notebooks would also be helpful to guide the testing process, so it knows what you've done and what is expected from your project, and can point you to specific examples in that code that can guide you. 
- Address any missing or non-functional elements in your project and repeat the test.
- Include a document (preferably a PDF of your AI chat) that contains the entirety of your conversation (_all prompts_ used and _all AI responses_) for this testing process.
- AI should generally _not_ be writing code for you — you already have the building blocks in your in-class notebooks and my provided keys. In fact, _you should have (and explain in your video) a good reason for any code I have provided that you change._ However, it may be helpful for debugging, getting you out of jams, brainstorming the build process, planning ways to make sure you are fulfilling the requirements, and directing your attention to relevant examples in the in-class notebooks. If you use it for any of these purposes, include a PDF showing the entirety of those discussions.

The above will count for 10% of your project grade. (# of requirements met / 3 or 4 * 0.1)


### Video walkthrough

5 minutes MAX, in which you explain (one point each):

- Your basic understanding of how your application works
- The purpose of your chatbot
- How and why you chose the texts you chose
- How and why you constructed your prompt instructions the way you did
- A demonstration of your code and visualizations (i.e., sending questions to your chatbot and showing the answers it returns)
- _Explanations of how you used AI to plan, assist, and/or test your scraper and analysis._

The above will count for 20% of your project grade. (# of requirements met / 6 * 0.2)


## Completion and assessment

Upload all code, the video, AI chat logs, and any other relevant files to Canvas by the deadline.

Your grade will be determined by whether or not you accomplished the objectives laid out by the bullet points above (70%), the quality of your AI-assisted testing (10%), and the quality of your explanations and reasoning in the video (20%).