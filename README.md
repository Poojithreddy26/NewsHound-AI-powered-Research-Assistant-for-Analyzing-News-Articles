# NewsHound-AI-powered-Research-Assistant-for-Analyzing-News-Articles
An AI-powered research assitant which helps us in extracting information over provided articles and helps in analyzing the vague and large articles.

# It is developed upon Langchain toolkit.
It helps in extracting information in the news articles which we provide through URL Loaders and uses OpenAI Embeddings to capture the embeddings and store it over FAISS vector database which helps in faster retrieval.

There are it is deployed over streamlit application to be accessible in the UI.

The installation steps are as follows:

1.Create an environment where you install all the dependencies by 
 'python -m install requirements.txt'

2.Get the OpenAI secret key and provide it over env.txt

3.Finally, Run "streamlit run main.py" which runs the application .

if you are running it on local,you can access the application on 'localhost:8501'