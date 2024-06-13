# Tasks

### Cloning the repository

Clone the repository using the command below :
```bash
git clone https://github.com/BosovPN/fastapi_tasks.git
```

Move into the directory where we have the project files : 
```bash
cd fastapi_tasks
```

### Running the App

Creating a docker image
```bash
docker build . --tag fastapi_app
```

Running docker image
```bash
docker run -p 80:80 fastapi_app
```
