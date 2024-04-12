First download the git cli

Application url:
[HSimpleFlaskApp](https://shortflaskapp-397fef696962.herokuapp.com/)

## To Start Machine Learning project follow the below steps.

### Software and account Requirement.

1. [Github Account] 
2. [Heroku Account]
3. [VS Code IDE]
4. [GIT cli]
5. [GIT Documentation]
6. [IpynKernel]
7. [Anaconda]
8. [Docker]

Create conda virtual environment
```
conda create -p venv python==3.11.5 -y
```
```
conda activate venv/
```
Install the necessary packages and libraries 

```
pip install -r requirements.txt
```

Adding files to git
```
git add .
```

OR
```
git add <file_name>
```


To check the git status 
```
git status
```
To check all version maintained by git
```
git log
```

To create version/commit all changes by git
```
git commit -m "message"
```

To send version/changes to github
```
git push origin main
```

To check remote url 
```
git remote -v
```

To setup CI/CD pipeline in heroku the following 3 information is needed

1. HEROKU_EMAIL 
2. HEROKU_API_KEY 
3. HEROKU_APP_NAME 

BUILD DOCKER IMAGE
```
docker build -t <image_name>:<tagname> .
```
> Note: Image name for docker must be lowercase


To list docker image
```
docker images
```

Run docker image
```
docker run -p 5000:5000 -e PORT=5000 f8c749e73678
```

To check running container in docker
```
docker ps
```

Tos stop docker conatiner
```
docker stop <container_id>
```



```
python setup.py install
```


Install ipykernel

```
pip install ipykernel
```


Data Drift:
When your datset stats gets change we call it as data drift
