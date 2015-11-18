# myProject1
Adding file

Create your repo on Github
git init
git add teste.odt #making github acknowledges the file 
git status #cheking what you have in the folder
git commit -m “Add teste.odt”
git remote add origin https://github.com/account/project
git remote -v #check 
git push origin master

# Add second file 
git add teste2.odt
git commit -m "Add teste2.odt"
git push -u origin master 
# I changed a file remotely so I need to sync them
git pull https://github.com/acsouza/myProject1.git 
git push -u origin master

