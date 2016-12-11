create a local repository


1¡¢or create a new repository on the command line

echo "# friendlyarm_linux3.0.86" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin git@github.com:ShengwenQin/friendlyarm_linux3.0.86.git
git push -u origin master




2¡¢push an existing repository from the command line

git remote add origin git@github.com:ShengwenQin/friendlyarm_linux3.0.86.git
git push -u origin master

