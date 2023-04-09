# Flask-Blog-Project
There is a basic flask blog project can used production environment.

Just clone and run ** python run.py ** enjoy!!!

or 

# Create .flaskenv file

must enter app
FLASK_APP=app

Chose True or False
FLASK_DEBUG={True/False}

For building Dockerfile preapre expected environment
docker build -t flaskblog:0.0.1 .

# For up your docker container

docker run -d -p 5052:5000 flaskapp:0.1.1

GO http://127.0.0.1:5052 !
