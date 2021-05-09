# Your first steps with Git and GitHub


### 1- Create an account on GitHub: https://github.com <br>
### 2- Download Git: https://git-scm.com/downloads <br>
### 3- Select a folder in your PC and create a file <br>
### 4- Set up your Git account <br>
```
git config --global user.name "username"
```
```
git config --global user.email "name@example.com
```
Check your account details:
```
git config --global --list
```
### 5- Initialise a Git reporsitory <br>
Go to your working directory:
```
cd Documents/MyProject
```
```
git init
```
![image](https://user-images.githubusercontent.com/83605634/117583224-e7f8f880-b0fd-11eb-83f1-65921037c324.png)

The .git folder has been created!
### 6- Stage your file(s) for commit
```
git add . # stage all files in the working directory
```
If you want to stage specific files:
```
git add circle.py
```
Check the list of staged files:
```
git status
```
![image](https://user-images.githubusercontent.com/83605634/117582988-b6336200-b0fc-11eb-87d9-4ffad9592c87.png)
### 7- Commit your files/changes
```
git commit -m "My first commit!"
```
![image](https://user-images.githubusercontent.com/83605634/117583519-7457eb00-b0ff-11eb-8f6a-bfe9d31b0b2e.png)
### 8- Push the changes from local repository to remote repository
We need first to define the remote repository URL.
<em>Origin</em> is the default name of the remote repository.
```
git remote add origin remote_repo_URL
```
List your connections to remote repositories:
```
git remote -v
```
![image](https://user-images.githubusercontent.com/83605634/117583816-2e038b80-b101-11eb-9e02-df9d66ffb57c.png)
You can know push the changes from your local repository to your remote repository.
```
git push -u origin master # master refers to the master branch in the remote repository.
```
Check your repository on GitHub. <br>
First, switch to the master branch:<br>
![image](https://user-images.githubusercontent.com/83605634/117584310-1d084980-b104-11eb-909f-69c4eff62bbe.png) <br>
Now, you should see your file!

![image](https://user-images.githubusercontent.com/83605634/117584275-f0ecc880-b103-11eb-896b-dae7d2d7c4d5.png)

### 9- Make changes to your local files
To see the changes (not staged yet):
```
git diff
```
![image](https://user-images.githubusercontent.com/83605634/117584627-f3502200-b105-11eb-9a53-b56798c9ca1a.png)

