# Rasa-Introduction-Chatbot

### Create environment

python3 -m venv env
source env/bin/activate

pip install flask uwsgi
pip list 

pip freeze > requirements.txt

export FLASK_ENV=run.py 
FLASK_ENV=development
flask run

### Run Flask app Mode Debug

python run.py 




### Docker Compose
docker-compose build
docker-compose up
docker-compose up --build

docker-compose down


