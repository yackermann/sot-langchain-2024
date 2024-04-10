# Summer of Tech 2024 - Langchain Crash Course


## Introduction

To get started, you will need to do some setup. First and foremost you need to know that all examples are done in Jupyter Notebook format. You can use Jupyter Lab, or simply Visual Studio Code. 

Next you need to setup virtual environment. If you have never used `python virtualenv`, here is a great tutorial to get you started: [Python Virtual Environment](https://realpython.com/python-virtual-environments-a-primer/), or you can watch this video tutorial https://www.youtube.com/watch?v=IAvAlS0CuxI.

Once you have setup your virtual environment, you can install the required packages by running the following command:

```bash
pip install -r requirements.txt
```

If you have issues installing packages, try setting up your environment to `python3.10`.

Now rename `example.env` to `.env` and add your API keys.

You ready to rock.

## Notes

- LLM providers

To play with this code you need LLM provider. If you want easy setup, for under $10 you can get OpenAI account here https://platform.openai.com/. It requires pre-payment to use API, but $10 will be enough for a lot of play.

If you want something more advanced, you can run LLM models locally using [Ollama](https://ollama.com/library). It's free, open source, but you need a little powerful machine. The smallest LLMs, like Mistral7b will need around 7GB of storage, and machine with at least 16GB of RAM. I run it using my M2 Macbook air and it works great.

There are many other providers like Hugging Face, Amazon Bedrock, Google Gemini, etc. You can use any of them, but you will need to adjust the code accordingly.


- PineconeDB

To setup pinecone db, go to https://www.pinecone.io/ and sign up for an account. Once you have an account, you can create a new index and get the API key. You can then use this API key to connect to the pinecone db.

If you use OpenAI, use "Setup by model", and select "text-embedding-3-large", which would give you dimension of 3072, and cosine similarity.

If you use [Ollama](https://ollama.com/library) see model specific instructions.


- Courses to play:

1. Free course on Langchain from Activeloop  - https://learn.activeloop.ai/courses/langchain
    - If you struggle you can see my solutions here: https://github.com/herrjemand/activeloop-langchain
2. Damien Benveniste Introduction to Langchain Udemy - https://www.udemy.com/course/introduction-to-langchain/?couponCode=ST8MT40924 ($13.99 as 10/04/2024. Normal price $69.99)
    - If you have technical issues, you can see my code here; https://github.com/herrjemand/udemy-langchain
3. Free Deeplearning.ai Mini Courses - https://www.deeplearning.ai/short-courses/
4. Deeplearning.ai Coursera Paid Courses - https://www.deeplearning.ai/courses/
5. Deeplearning.ai x Stanford Coursera ML Specialization - https://www.coursera.org/specializations/machine-learning-introduction?utm_campaign=WebsiteCourses-MLS-TopButton-mls-launch-2022&utm_medium=institutions&utm_source=deeplearning-ai
6. Deeplearning.ai GetAI Coursera Course - https://www.deeplearning.ai/courses/generative-ai-with-llms/