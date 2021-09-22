# How to use github with git bash...

- How to use github or git bsah. all commend and some video link
- Git Repository Edit,update,branching file or folder menualy from "Find file" beside the 'Clone or download'..
- And insert for drag and drop the Repository

#### Early upload Command
```
git add .
git commit -m "first commit"
git push
```
#### Configure Git
1. In your shell, add your user name:
         git config --global user.name "your_username"
2. Add your email address:  
        git config --global user.email "your_email_address@example.com"
3. o check the configuration, run:  
        git config --global --list
        
The --global option tells Git to always use this information for anything you do on your system. If you omit --global or use --local, the configuration applies only to the current repository.

#### Necessary Command  
```
ls
mkdir
cd
git init	
git remote add origin <gitlink>
git remote -v
git add .    or    git add *   or   git add -A    
git commit -m "first commit"
git pull
git push origin master
git log
git status
git --version
git help
__git
git config --global user.email "you@example.com"
git config --global user.name "Your Name"



ls = List all the files in the current directory

mkdir = To create new folder

cd = To change the directory

git init = Initializes the git in this path. You can see the .git hidden files after this command gets executed.

git remote add origin [gitLink] = gitLink denote the place where your code is stored in the remote repository

git add . = Add all the files in the directory

git commit -m "First commit" = It establishes a connection with local repository

git pull = Fetch from and integrate with another repository or a local branch

git push origin maste = It establishes a connection with a remote repository and upload your source code or files to GitHub

git log = Comment see

git status = The git status command displays the state of the working directory and the staging area

git --version = For check gitbash current version

git help = Its given all help command 

__git = Get git Command

To set your account's default identity.


```

#### Branching Command
```
git clone <link> -b <brance name>
Example: git clone https://github.com/Rasel120/How_to_create_and_use_branch.git -b person1
````

#### How to create a new folder in same repository
```
Go to the folder inside which you want to create another folder.
Click on New file.
On the text field for the file name, first write the folder name you want to create.
Then type / . ...
You can add more folders similarly.
```

#### Big MB file loaded problem solution Command
```
git config --global http.postBuffer 157286400
```

#### High Storage Limit
Let us say this first: git is not a backup utility. You do not use git for online storage or backups. It’s inefficient for that, and it bogs down the servers and your computers. That said, however, when you get a large number of commits and pushes and branches, your repo can start packing some serious mass.

A benefit of GitHub is that you don’t get charged for that storage. Even on a free plan. There is a hard 100-gigabyte cap on GitHub repositories, though they recommend it being under 1gb (which many of them will be). The file uploads are limited to 100mb for command line and 25mb for web uploads.

Bitbucket, though, only allows free users 1gb total. Instead of requesting that you keep it below 1gb and then emailing you when you reach 75 (which is a very large range and kind of an odd choice), Atlassian pushes you toward the paid plans at 1+gb.

Now, that is 1gb per repo, so you can have multiple repos for free like that. But you don’t have to worry about that with GitHub. Both of them offer large file solutions, too (Bitbucket’s is here, and GitHub’s is here).


