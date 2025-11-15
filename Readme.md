pip install -r requirements.txt

docker-compose up --build

docker-compose down

docker-compose run api python -m unittest discover