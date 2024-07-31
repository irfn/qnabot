# qnabot

1. Setup dependencies

`brew install ollama`

`poetry install`

3. Run Litellm proxy

`ollama pull llama3:instruct`

`poetry run litellm --model ollama/llama3:instruct`

3. separately run app

`env AUTOGEN_USE_DOCKER=False poetry run python main.py`

4. you may have to remove tmp folder on rerun

TODO seperate build chroma db from inference flow
