# learnGit
This is to learn git and git hub

# Steps and Impotant commands 

Reference:https://youtu.be/J_Clau1bYco

#Save credentials for specific (default 15 minute but set to 1 hr) time 
git config --global credential.helper cache
git config --global credential.helper 'cache --timeout=3600'

git config --global user.name "Rvadrabade"
git config --global user.email rahulsomeshwarv@gmail.com

git clone https://github.com/Rvadrabade/learnGit.git
git add steps.txt
git status
git commit -m "steps to start" steps.txt
git push -u origin master

#After each modification 
git add or git commit -a -m "some message"
git push -u origin master