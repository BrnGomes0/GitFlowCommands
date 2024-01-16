# Commands Git Flow (How use GitFlow for projects in Teams)

### GitFlow initialization:
`git flow init`
<br>
<img
  src='https://github.com/BrnGomes0/GitFlowCommands/assets/132568509/725dd1de-87f0-4f24-9dad-0b55607167c2'
  width='160px'
  height='160px'
  />


### Commands Generic git commands to commit to develop:
**This commands is generic git commands (Normal):**
<br>
`git status`
<br>
`git add <file_name>` or `git add .`
<br>
`git commit -m "Message of Commit"`
<br>

### Command to access another existing branch:
`git checkout <branch_name>`

### Command see the tagas in branchs:
`git tag` -> That command you can see all tags, but you can see only in develop or master/main
<br>
<img
  src='https://github.com/BrnGomes0/GitFlowCommands/assets/132568509/07606d20-5c96-456a-87a5-44722dcad885'
  width='160px'
  height='160px'
  />
<br>
<img
  src='https://github.com/BrnGomes0/GitFlowCommands/assets/132568509/e520e429-317c-4a99-bb49-145500f7225a'
  width='160px'
  height='160px'
  />
### Creating a new features:
**That branch work for create a new feature**
<br>
`git flow feature start css`-> That command will create a branch [feature/css]

### Finish or Publish a feature:
`git flow feature finish css` -> Delete a branch and do the merge in develop (All automatic for Git Flow)
<br>
`git flow feature publish css ` -> Up in remote repository on Github
<br>
### Creating a new Release:
**That branch work for Test the application**
<br>
`git flow release start 1.0` -> That command will create a branch [release/1.0]
<br>
<img
  src='https://github.com/BrnGomes0/GitFlowCommands/assets/132568509/da78b9c8-7d31-4433-af94-d3f3260a323f'
  width='160px'
  height='160px'
  />

### Finish or Publish a Release:
`git flow release finish 1.0` -> When you enter that command, git flow show the file for you put a message in tag
<br>
<img
  src='https://github.com/BrnGomes0/GitFlowCommands/assets/132568509/acf40555-9e6f-44bd-b5ea-80d9ee897d43f'
  width='160px'
  height='160px'
  />
<br>
`git flow release publish 1.0`

### Creating a Hotfix:
**That branch it is for change simples errors**
<br>
`git flow hotfix start 1.1` -> That command will create a branch [hotfix/1.1]
<br>
<img
  src='https://github.com/BrnGomes0/GitFlowCommands/assets/132568509/862844e2-2b6b-4644-83dc-69383efff1d3'
  width='160px'
  height='160px'
  />
<br>

### Finish or Publish a Hotfix:
`git flow hotfix finish 1.1` -> When you enter that command, git flow show the file for you put a message in tag
<br>
<img
  src='https://github.com/BrnGomes0/GitFlowCommands/assets/132568509/8ae96cb5-88c3-4ba2-bdea-865a4eed9ff4'
  width='160px'
  height='160px'
  />
<br>
`git flow hotfix publish 1.1`
