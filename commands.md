$ git clone https://github.com/NixInTheWay/Recruitement-Git-Challenge-2026.git
This Command is used to clone the forked repository
$ cd Recruitement-Git-Challenge-2026
This is to change the current directory to the repository
$ echo "05-09-2026" > V-P-Bhuvan-Aditya.txt
Add the date to a file with my name
$ git add V-P-Bhuvan-Aditya.txt
Adds the text file to the repository under the main branch
$ git commit -m "05-09-2026"
Inserts the modified file into the repository
$ git log
To see the commit hash
$ git checkout -b V-P-Bhuvan-Aditya
Creates a new branch off main
$ echo "description f8d3fa96fdbe68245cc400d12d36eb51c614fea9"  > AM.SC.U4CSE26241.md
Writes the description and commit hash into the file
$ git add AM.SC.U4CSE26241.md
Adds the file to the repository under the name branch
$ git commit -m "Added self description"
Inserts the modified file into the repository
$ git checkout main
Switching the working branch to main
$ git merge V-P-Bhuvan-Aditya
merges the branch to the main.
$ echo "V P Bhuvan Aditya" >> README.md
Appending name into README.md
$ git add README.md
Adds the modified file to repository, this located in the root directory
$ git commit -m "Append name to README.md"
Inserts the modified file into the repository
$ echo "Peri Peri Chicken Al Faham" >> README.md
Appending my favourite dish
$ git commit -m "Added Favourite dish"
Commiting
$ git reset --hard HEAD\~1
resets the Repository to 1 commit before the current (HEAD\~1). It deletes both the commit history and what was done.

The Git tree has the 'main' branch and the 'V P Bhuvan Aditya' Branch in it, with README.md in the root directory. The main branch and  V-P-Bhuvan-Aditya branch are now merged and both share the files. They contain AM.SC.U4CSE26241.md  README.md  V-P-Bhuvan-Aditya.txt  commands.md

