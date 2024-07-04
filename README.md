# PDF2QUIZ
Website to convert any pdf into a quiz.

### Demo
Click on the image to view the demo video.
[![Video Title](https://github.com/CorruptEntity0982/PDF2Quiz/blob/main/Frontend/public/Thumbnail.png)](https://youtu.be/fk9oTbGQaKE)

### Install dependancies to run backend
```
pip install -r requirements.txt
```

### Install node modules to run frontend
```
npm install
```
### Setup OpenAi Api Key
Create a .env file in the root folder <br>
Add the following line and save the file <br>
```
OPENAI_API_KEY = your-openai-api-key-here
```

### How to run backend API
Change your directory to "backend"<br>
This starts the backend server
`python3 server.py`<br>

### How to run frontend server
Change your directory to "Frontend"<br>
This starts the frontend code 
`npm start`

### How to create a feature branch<br>
```
git branch feature-branch
git switch feature-branch
```

### Before starting any work, make sure your branch is upto date with main branch on the repository
Failing to do this may cause errors in pushing code and need for rebasing
```
git switch main
git pull origin main
```

### How to add files to main branch
Do this to update main branch on the repository:<br>
```
git checkout main<br>
git add .<br>
git commit -m "Add new files to feature branch"<br>
git push origin main<br>
```
 
### How to merge changes to main branch from feature branch
```
git switch main
git merge feature-branch  (Replace feature-branch with actual name of your feature branch)
```
