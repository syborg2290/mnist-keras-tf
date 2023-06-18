# Create virtual environment

- virtualenv venv
- source venv/bin/activate
- python -m pip install jupyter
- python -m ipykernal install --user --name=venv
- pip install tensorflow
- pip install matplotlib
- pip install pandas
- pip install seaborn

- pip freeze > requirements.txt
