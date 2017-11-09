# 01

- Someone has a project.

# 02

- Click "Fork" on GitHub.

# 03

- `git clone [my_url]`
- `git remote add upstream [their_url]`

# 04

- `git checkout -b my_branch`
- Do work; make commits.

# 05

- `git push origin my_branch`

# 06

- They put some new work on `master`.

# 07

- `git checkout master`
- `git pull upstream master`

# 08

- `git push origin master`

# 09

- `git checkout my_branch`
- `git merge master`

# 10

- `git push origin my_branch`

# 11

- Click "New Pull Request."
- Get comments; do work; make commits.

# 12

- `git push origin my_branch`

# 13

- They're happy. They click "Merge Pull Request."

# 14

- They click "Delete Branch."

# 15

- `git checkout master`
- `git pull upstream master`

# 16

- `git push origin master`

# 17

- `git branch -d my_branch`

# 18

- `git push origin :my_branch`
- Done!
