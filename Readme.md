# Commands Git Flow (How use GitFlow for projects in Teams)

### GitFlow initialization:
`git flow init`

### Commands Generic git commands to commit to develop:
This commands is generic git commands (Normal):
`git status`
`git add <file_name>` or `git add .`
`git commit -m "Message of Commit"`

### Command to access another existing branch
`git checkout <branch_name>`

### Command see the tagas in branchs
`git tag` -> That command you can see all tags, but you can see only in develop or master/main

### Creating a new features:
That branch work for create a new feature
`git flow feature start css`-> That command will create a branch [feature/css]

### Finish or Publish a feature:
`git flow feature finish css` -> Delete a branch and do the merge in develop (All automatic for Git Flow)
`git flow feature publish css ` -> Up in remote repository on Github

### Creating a new Release:
That branch work for Test the application
`git flow release start 1.0` -> That command will create a branch [release/1.0]

### Finish or Publish a Release:
`git flow release finish 1.0` -> When you enter that command, git flow show the file for you put a message in tag
`git flow release publish 1.0`

### Creating a Hotfix:
That branch it is for change simples errors
`git flow hotfix start 1.1` -> That command will create a branch [hotfix/1.1]

### Finish or Publish a Hotfix:
`git flow hotfix finish 1.1` When you enter that command, git flow show the file for you put a message in tag
`git flow hotfix publish 1.1`