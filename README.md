# How to use github with git bash...

- How to use github or git bsah. all commend and some video link
- Git Repository Edit,update file or folder menualy from "Find file" beside the 'Clone or download'..
- And insert for drag and drop the Repository

#### How to create a new folder in same repository
```
Go to the folder inside which you want to create another folder.
Click on New file.
On the text field for the file name, first write the folder name you want to create.
Then type / . ...
You can add more folders similarly.
```
#### Early upload Command
```
git add .
git commit -m "first commit"
git push

```
#### Big MB file loded problem solution Command
```
git config --global http.postBuffer 157286400
```


#### Necessary Command  
```
ls
mkdir
cd
git init	
git remote add origin <gitlink>
git remote -v
git add .    or    git add *   or   git add --all     
git commit -m "first commit"
git pull
git push origin master
git log
git status
git --version
git help


ls- List all the files in the current directory

mkdir- To create new folder

cd - To change the directory

git init- Initializes the git in this path. You can see the .git hidden files after this command gets executed.

git remote add origin [gitLink]- gitLink denote the place where your code is stored in the remote repository

git add .- Add all the files in the directory

git commit -m "First commit"- It establishes a connection with local repository

git pull- Fetch from and integrate with another repository or a local branch

git push origin master- It establishes a connection with a remote repository and upload your source code or files to GitHub

git log- Comment see

git status- The git status command displays the state of the working directory and the staging area

git --version- For check gitbash current version

git help- Its given all help command 


```
