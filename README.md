# ZHAW-MatchMaking Material

This repository contains notebooks used for brainstorming and building the *proof-of-concept* matchmaking bot. The bot is available here:</br></br>
[ZHAW MatchMaking Bot](https://github.com/przvlprd/zhaw-matchmaking-app)
</br></br>
The notebooks cover the steps from building the database with `MongoDB` by scraping raw user profiles from the ZHAW website, preprocessing this data and adding metadata, chunking the data with `LangChain` and adding it to a local vector database using `ChromaDB`.</br>

### Setup

- place your **OpenAI API key** inside `.env`

- create a virtual environment
```shell
# PowerShell
python -m venv env
.\env\Scripts\activate

# Linux / WSL
virtualenv --python python3.11 venv
source venv/bin/activate
```

- install the dependencies
```shell
pip install -r requirements.txt
```

- run jupyter notebook and open a file
```shell
jupyter notebook
```
