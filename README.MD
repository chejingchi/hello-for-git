# learn how to use git and github.


----------


### configure git
- check your version
`git —version`
you can see your git version.

- config your name and email
`git config —-global user.name "\<Your Name\>"`
add your name
`git config --global user.email "\<youremail@example.com\>"`
and your email

- create a git instance
`git init`
you need to create a new folder that you want to add to git.Then  go into it.You can use git init to create a new git instance for you

- find git status
`git status`
you can see the status of your git.![][image-1]

[image-1]:git-init.png "git-init"
- add and commit changes
`git add README.MD`
`git commit -m "commit message"`
or you can use `git commit -ma "commit message"` you will make all file that is add into git commit to git.
`git diff` show difference
`git add .` add all files changes

- add github account to git
`git config --global user.username <github username>`

- connect local to remote and push
`git remote add origin <URLTHATUCREATEINGITHUB>`
`git push origin master`

- fork and clones
fork is just click the fork button
`git clone <URLFORMGITHUB>`
