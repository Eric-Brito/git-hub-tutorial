# git-hub-tutorial

…or create a new repository on the command line
echo "# temp_dswa5_11-ac" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/Eric-Brito/temp_dswa5_11-ac.git
git push -u origin main
…or push an existing repository from the command line
git remote add origin https://github.com/Eric-Brito/temp_dswa5_11-ac.git
git branch -M main
git push -u origin main
 
Tip to get only the remote URL: git config --get remote.origin.url
Change remote origin: git remote set-url origin https://git-repo/new-repository.git
