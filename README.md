# windos-template
A simple template repository for developing python apps on Windows with the help with docker.

### To build and run with docker-compose:
```
docker-compose build
docker-compose up
```

### To build and run with docker:
```
docker build -t app:latest .
docker run --name app -d --rm app:latest
```

### In order to build the app from scratch:
```
python3 -m venv .venv
source .venv/bin/activate
pip3 install -r requirements.txt

pyhton3 app.py
```
