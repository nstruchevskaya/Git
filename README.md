# Git # 📌 

Git is available on every developer’s computer. It allows easy branching, merging and collaboration 🤝
Some git commands that I did.

## Task 1

##### Creating, cloning, pushing and pulling repositories  

git init nstruchevskaya                                         # Create repository with the same name as your username 
git clone git@github.com:nstruchevskaya/nstruchevskaya.git      # Clone repository on your computer to a separate folder
git clone git@github.com:testrusau/testrusau.git                # Clone from testrusau on your computer to a separate folder
cd testrusau                                                    # Go back
git push git@github.com:nstruchevskaya/testrusau.git main:main  # Push data from testrusau repository to your own one 
git commit -m "commited change description"                     # Open the README.md file and replace each block with a separate commit 
git push 

## Task 2


##### Creating, adding remote repositories  

git init sql                                                   # Create separate repository for portfolio  
git remote add sql https://github.com/nstruchevskaya/sql.git   # Connect to repository remotely 
README.md edited manually                                      # Add links to your repositories to the README.md file
git commit -m "commited changed description"                   # Commit changes
git push                                                       # Push changes to remote repository                                                     
