# FastAPI Tutorial
This repo is for learning how to use FastAPI.

## Tutorial
The code in this tutorial is found in the official documentation for FastAPI: https://fastapi.tiangolo.com/.

# Docker

## Building the docker image
```
sudo docker build -t fastapi-image .
```

## Starting the docker container
```
sudo docker start fastapi-container
```

### Accessing the app
#### Docs

## Running the app locally
### Requirements
Make sure you have installed the requirements found in requirements.txt in a virtual environment using tools such as conda or virtualenv.

### Running the code
```
uvicorn main:app --reload
```