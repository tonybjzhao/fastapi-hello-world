[![Board Status](https://dev.azure.com/tonyzyt/7d753a5e-ed2b-4c2e-99eb-6de025aa56ba/06487bbc-ce53-4ab7-94ee-652e066164c3/_apis/work/boardbadge/6af6314b-4125-47a2-afb1-fb69cd01fd28)](https://dev.azure.com/tonyzyt/7d753a5e-ed2b-4c2e-99eb-6de025aa56ba/_boards/board/t/06487bbc-ce53-4ab7-94ee-652e066164c3/Microsoft.RequirementCategory)
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
docker run -p 80:80 -it fastapi-image
```

## Running the app locally
### Requirements
Make sure you have installed the requirements found in requirements.txt in a virtual environment using tools such as conda or virtualenv.

### Running the code
```
uvicorn main:app --reload
```