## machine_learning_proj1.


### Software and Account Requirements.

1. [Github account](https://github.com/)

2. [Heroku account](https://dashboard.heroku.com/)

3. [VS code IDE](https://code.visualstudio.com/)

4. [Git CMD](https://git-scm.com/downloads)
5. [GIT Documentation](https://git-scm.com/docs/gittutorial)

Creating conda environment
```
conda create -p env python==3.7 -y
```
Activate conda environment 
```
conda activate env/
```

or 
```
conda activate env
```

Install requirements.txt
```
pip install -r requirements.txt
```

Run python app in terminal

```
python app.py
```

> Note: To ignore file or folder from git we can write name of file/folder in .gitignore file
```
Environments 
ml1venv
ml1venv/
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
To send version or changes to github
```
git push origin main
```
To check remote url
```
git remote -v
```
To set up CI/CD pipeline n heroku we need 3 information
1.HEROKU_EMAIL
2.HEROKU_API_KEY
3.HEROKU_APP_NAME

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
docker run -p 5000:5000 -e PORT=5000 33fb0d57530b
```
browser
```
http://localhost:5000/
```
To check running container in docker
```
docker ps
```

To stop docker container 
```
docker stop <container_id>
```

```
python setup.py install
```
