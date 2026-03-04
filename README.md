# 📌 git


Git is a version control system available on every developer’s computer. It allows easy branching, merging, collaboration. 


Some tasks that I did.


## Easy navigation


- [Creating, cloning, pushing and pulling repositories](#task-1)
- [Creating, adding remote repositories](#task-2)


## Task 1


##### Creating, cloning, pushing and pulling repositories  
```git
git init nstruchevskaya                                           # Create your repository with the same name as username
git clone git@github.com:nstruchevskaya/nstruchevskaya.git        # Clone your repository on your computer to a
git clone git@github.com:testrusau/testrusau.git                  # Clone github.com/testrusau/testrusau on your folder
cd testrusau                                                      # Go back
git push git@github.com:nstruchevskaya/testrusau.git main:main    # Push data from testrusau repository to your repository
git commit -m "commited changes"                                  # Open the README.md file and replace each block
git push 


```
## Task 2


##### Creating, adding remote repositories  
```git
git init sql                                                   # Create separate repository for portfolio item
git remote add sql https://github.com/nstruchevskaya/sql.git   # Declarie repository remotely 
README.md edited manually                                      # Add links to your repositories to the README
git commit -m "Change description"                             # Commit  changes
git push                                                       # Push changes to remote repository








```

