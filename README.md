# Machine-Learning-Project-End-to-End
This is the first End to End ML project with complete CICD Pipeline
Housing_Prediction_Dcoker_CI-CD-Pipeline_Project
Creating conda environment -> conda create -p venv python==3.7 -y

for checking conda -> conda --version

for activate conda environment -> conda activate venv/

installing requirments

-> pip install -r requirements.txt

to run app.py

-> python app.py

to add files in git -> git add . or git add filename

to ignore file or folder from git we can write name of file or folder in .gitignore file

to check git status -> git status

to check all version maintained by git -> git log

to create version/commit all changes by git

-> git commit -m "message"

to send version/changes to github

-> git push origin main

to check remote url

-> git remote -v Start Machine Learning project. Software and account Requirement. Github Account Heroku Account VS Code IDE GIT cli GIT Documentation Creating conda environment

conda create -p venv python==3.7 -y conda activate venv/ OR

conda activate venv pip install -r requirements.txt To Add files to git

git add . OR

git add <file_name> Note: To ignore file or folder from git we can write name of file/folder in .gitignore file

To check the git status

git status To check all version maintained by git

git log To create version/commit all changes by git

git commit -m "message" To send version/changes to github

git push origin main To check remote url

git remote -v To setup CI/CD pipeline in heroku we need 3 information

HEROKU_EMAIL = surzchandan@gmail.com

HEROKU_API_KEY =e98f34ea-f5a0-4b0d-a61c-6b5a7fc1aefd

HEROKU_APP_NAME = ml-project-end-to-end 

BUILD DOCKER IMAGE

docker build -t <image_name>: . Note: Image name for docker must be lowercase

To list docker image

docker images Run docker image

docker run -p 5000:5000 -e PORT=5000 f8c749e73678 To check running container in docker

docker ps Tos stop docker conatiner

docker stop <container_id>

python setup.py install Install ipykernel

pip install ipykernel