# My django girls tutorial training.

This is my django girls tutorial training.

The environment was built on docker.

## Requirements

The file requires the following to run:

- docker and docker-compose

## Usage

### git clone this repository

To use this, clone the repo.

### Structure

```
.
├── db/
│   └── docker-entrypoint-initdb.d/
├── db.dockerfile
├── docker-compose.yml
├── requirements.txt
├── web/
└── web.dockerfile
```

### Usage

Executing the following command in the repository, two container will be built.

```
docker-compose up -d
docker container exec -it {CONTAINER_NAME} python {PROJECT_NAME}/manage.py runserver 0.0.0.0:8000
```

Thank you.

## Author
[Hoda](https://hodalog.com/)
