# Boilerplate-Standards
Boilerplate starter repo that has standard techcoop documentation file templates

Start repo here, or merge into new project to populate documentation.

# Requirements

1) A will to do things a standard way

# Installation

### For a new repo

```bash

# 1) Clone this repo
git clone git@github.com:techcoop/boilerplate-standards.git myproject 

# 2) Navigate to this folder
cd myproject

# 3) Change remotes to point to your own endpoint
git remote remove origin
git add origin git@github.com:YOUR_NAME/myproject.git

# 4) Replace YOUR_NAME with your actual name 

# 5) Replace YOUR_NAME with your actual name
git commit -m "Resolves merge conflicts"
git push origin master


```

### Copy into existing project

```bash

# 1) Clone boilerplate-standards repository
git clone git@github.com:techcoop/boilerplate-standards.git

# 2) Navigate to your existing project
cd myproject

# 3) Copy files over other repo, will not overwrite (-n)
# (You can do this manually to) 
cp -rn ../boilerplate-standards/* .

# 4) Replace YOUR_NAME with your actual name 

# 5) Finalize changes
git add .
git commit -m "Resolves merge conflicts"
git push

```
?? If you are not familiar with resolving merge conflicts, try [here](https://githowto.com/resolving_conflicts) 

### Pull into directly into repository
```bash

# 1) Navigate to your existing project
cd myproject

# 2) Pull in upstream
git remote add upstream git@github.com:techcoop/boilerplate-javascript-library.git
git pull upstream --allow-unrelated-histories

# 4) Resolve any conflicts

# 5) Replace YOUR_NAME with your actual name 

# 6) Finalize changes and push
git add .
git commit -m "Resolves merge conflicts"
git push
```

# Testing

# Examples
Examples are located in /examples

# Contributors
[YOUR_NAME][admin]


[admin]: https://github.com/YOUR_NAME