# QA-Chatbot

This is a **QA chatbot**, that answers question related to a fictional company named **Red30 Shoes**. It also stores context with chat history in the memory.
You can access the application using UI and as a CLI app.

## Tech stack

- Streamlit
- OpenAI
- Langchain
- ChromaDB
- Python

## Running the application

Create a virtual environment

```bash
python -m venv env
```

Now install the dependencies by running

```bash
pip install -r requirements.txt
```

Then copy .env.sample and create a .env file. And add your openai key to your application.

Then for starting the application

```bash
streamlit run app.py
```

## Application UI

![img1](/images/streamlit.png)

For running the application in cli

```bash
python main.py
```
