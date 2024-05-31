<div align="center">
## Tasks
</div>

### Cloning the repository

Clone the repository using the command below :
```bash
git clone https://github.com/BosovPN/fastapi_tasks.git
```

Move into the directory where we have the project files : 
```bash
cd fastapi_tasks
```

### Windows
Create a virtual environment :
```bash
# Installing virtual environment
pip install virtualenv

# Then we create our virtual environment
py -m venv venv
```

Activate the virtual environment :
```bash
.\venv\Scripts\activate
```

Install the requirements :
```bash
pip install -r requirements.txt
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
