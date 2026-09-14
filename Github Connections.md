<h3>NEW LOCAL PROJECT → COMPLETELY EMPTY GITHUB REPOSITORY</h3>

cd "C:\\path\\to\\project"



git init

git add .

git commit -m "Initial commit"

git branch -M main

git remote add origin https://github.com/USERNAME/REPOSITORY.git

git push -u origin main
 

<h4>After that, whenever you make changes:</h4>

git add .

git commit -m "Describe your changes"

git push


<h3>NEW LOCAL PROJECT → GITHUB REPOSITORY ALREADY HAS COMMITS</h3>
 

cd "C:\\path\\to\\project"



git init

git add .

git commit -m "Initial commit"

git branch -M main

git remote add origin https://github.com/USERNAME/REPOSITORY.git

git pull --rebase origin main

git push -u origin main


<h4>After that, whenever you make changes:</h4>


git add .

git commit -m "Describe your changes"

git push


<h3>IMPORTANT NOTES</h3>


git add .

→ Add all changed/untracked files.



git add filename.extension

→ Add only the specific file.



git pull --rebase origin main

→ Get the latest changes from GitHub and put your local changes on top of them.



git push -u origin main

→ Push your local main branch to GitHub and remember the connection.

