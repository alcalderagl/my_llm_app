# my_llm_app
[![llm with rag](https://github.com/alcalderagl/my_llm_app/actions/workflows/devops.yml/badge.svg)](https://github.com/alcalderagl/my_llm_app/actions/workflows/devops.yml)

1. Create a Python Virtual Environment `python3 -m venv ~/.venv ` or `virtualenv ~/.venv`
2. Accesing virtual environment `vim ~/.bashrc`

3. Create  `Makefile`, `requirements.txt`, `main.py`, `Dockerfile`,`mylib/__init__.py`
4. populate `Makefile`
5. Build CLI using python Fire library `./cli-fire.py --help` (`chmod +x cli-fire.py`)