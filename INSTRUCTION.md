Local Installation

1) pip install -r requirements.txt 
2) python manage.py migrate
3) python manage.py runserver


DockerHub - https://hub.docker.com/repository/docker/vanyas627/todoapp/general

Image: docker build -t todoapp:1.0 .

Run Container: docker run -p 8080:8080 todoapp:1.0

Open the app in browser: http://localhost:8080