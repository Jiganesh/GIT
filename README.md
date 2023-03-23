**Adding a local repository to GitHub with GitHub CLI**
`git init -b main`
`git add . && git commit -m "initial commit"`
`gh repo create`

select "Push an existing local repository to GitHub" and enter the desired name for your repository and select necessary options for further questions.


**Check changes done in working directory**
`git status`

**Add changes from working directory to staging area** 
`git add <filename/directory>`

**Stage chunks in files, this command provides more control on changes you want to add to staging area**

`git add -p <filename>` 

Begin an interactive staging session that lets you choose portions of a file to add to the next commit. This will present you with a chunk of changes and prompt you for a command. Use y to stage the chunk, n to ignore the chunk, s to split it into smaller chunks, e to manually edit the chunk, and q to exit.


**Remove changes from the staging area**
`git restore --staged <filename>`


**Capture a snapshot of changes in stagging area**

`git commit -m "<message>"`

For more detailed message
`git commit `


**Viewing overall history of the project**
`git log`

**Viewing overall history of the project in one liner log messages**
`git log --oneline`
