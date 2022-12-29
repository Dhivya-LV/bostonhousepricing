# bostonhousepricing

# software and tools requirement

1. [GithubAccount](https://github.com/Dhivya-LV/bostonhousepricing)
2. [pythonanywhere](https://www.pythonanywhere.com/)
3. [VSCodeIDE](https://code.visualstudio.com/)
4. [GitCLI](https://git-scm.com/docs)

Create a new repository in github
---------------------------------
open github -> Add README -> Add gitignore:Python -> Choose license:Apache License 2.0 -> create repository

Clone this repository inorder to commit the code(model) in this commits
---
Code -> copy the github URL -> copy the folder path required -> go to the cmd prompt -> go to the folder path -> git clone github URL -> check the folder -> copy the ipynb and pkl files into this folder inorder to commit the changes

create a new environment
---
```conda create -p venv python==3.7 -y```

To see the environment
```conda info --envs```

To remove the environment and its path and folder
```conda remove --name bhpvenv```
```conda remove -p bhpvenv --all```

to activate the environment
```conda activate bhpvenv\```

then create requirements.txt file to install the libraries required for the project

then in terminal -> ```pip install -r requirements.txt```

then configure the git cli using
```git config --global user.name "Dhivya N"```(the item inside quotes to configure for the first time only)
```git config --global user.email "dhivya.n@latentview.com"```

gitignore contains path which we dont want to commit to main branch
Inorder to not commit the changes to the branch, include that path in gitignore

```git add filename``` -> will add the file to be committed -> stages the files
```git add .``` -> to add all the files that has been changed 

```git status``` -> will show the files to be committed
```git commit -m "commit message"```-> will stage all the files and commit the changes

git push <remote> <branch> -> ```git push origin main```