## python version is 3.11

## load necessary dependencies with "pip install -r requirements.txt"

## secrets.toml is not uploaded in github. so create a new secrets.toml with your own secrets.toml 

# if 아래 Error 발생하면
## ModuleNotFoundError: No module named 'streamlit.cli'  
## fix: pip install --upgrade streamlit  (version: 1.33.0)

# anaconda 에 설치된 python version 이 3.10 이하이면 아래 방식으로 python upgrade
conda search python
conda install python=3.11.7
conda update --all
conda activate or restart the system
## 
