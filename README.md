# How to use git

## Cloning Repo
1. `git clone https://github.com/chloechak/githubattempt.git`
2. Change directory to the repo `cd githubattempt`


## Starting new changes
1. Change to main branch `git checkout main`
2. Pull in any updates to the main branch `git pull`
3. Switch to your own branch `git checkout -b "my_branch_name"`

## Committing Changes
4. Make your changes
5. Add your changes to be commited `git add file1 file2` (use `git add .` to add all file`)
6. Commit your changes `git commit -m "this is a commit message"
7. Run `git push --set-upstream origin my_branch_name`
8. `git push`

## Merging changes into the main branch
1. Go to github, click branch, select your branch
2. Click "Compare and Pull Request"
3. Someone needs to review and approve the pull request
4. Merge pull request

