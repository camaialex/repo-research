`git --version`

`touch .gitignore` to create .gitignore in the root folder

`vim .gitignore` to modify the .gitignore file

`git clone`: initial setup; make sure SSH is configured and added to the respository

Set up `.gitignore` to ignore default system files and personal settings

`git add .` stages file(s). Use the period to stage all changes.

`git commit -m "message"`

`git push`

`git reset` for when you mess up the stage

`git status` to check which files have been staged

`git stash` **very useful for conflicts** stores a local copy of the repository so that you don't lose overwritten conflicting file versions (needs to be done in terminal/cmd)